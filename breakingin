--// Snow Hub
local SnowLib = loadstring(game:HttpGet(("https://snowhub.dev/developer/library"), true))()
local Window = SnowLib:Window("Break In (Story)")
local Main = Window:Tab("Lobby")
local MainMan = Window:Tab("Main")
local Items = Window:Tab("Items")
local Teleports = Window:Tab("Teleports")
--// Main
Main:Label("                                    Must Be In Lobby")

Main:Button("The Officer", function()
local A_1 = "Gun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Main:Button("The Swat", function()
local A_1 = "SwatGun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)
--// MainMan
MainMan:Button("Befriend Cat", function()
local Target = game:GetService("ReplicatedStorage").RemoteEvents.Cattery;
Target:FireServer();
end)

MainMan:Button("Insta Heal", function()
for i = 1, 200 do
	    
local A_1 = "Cat"
local Event = game:GetService("ReplicatedStorage").RemoteEvents.Energy
Event:FireServer(A_1)
	
end
end)

MainMan:Button("Kill Enemies", function()
   for i,v in pairs(game.Workspace.BadGuys:GetChildren()) do
	
	        for i = 1, 50 do
	
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,10)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,9)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
	
	        end
	
	        end
end)

MainMan:Button("Open Safe", function()
if workspace:findFirstChild("CodeNote") then
	game.ReplicatedStorage.RemoteEvents.Safe:FireServer(workspace.CodeNote.SurfaceGui.TextLabel.Text)
	end
end)
--// Items
Items:Button("Get Apple", function()
local args = {
    [1] = "Apple"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Chips", function()
local args = {
    [1] = "Chips"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get BloxyCola", function()
local args = {
    [1] = "BloxyCola"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Lollipop", function()
local args = {
    [1] = "Lollipop"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Bat", function()
local args = {
    [1] = "Bat"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Teddy", function()
local args = {
    [1] = "TeddyBloxpin"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Sword", function()
local args = {
    [1] = "LinkedSword"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Plank", function()
local args = {
    [1] = "Plank"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Medkit", function()
local args = {
    [1] = "MedKit"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Pizza (Must Be Pizza On Table)", function()
local args = {
    [1] = "Pizza"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Cookie", function()
local args = {
    [1] = "Cookie"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)

Items:Button("Get Cure", function()
local args = {
    [1] = "Cure"
}

game:GetService("ReplicatedStorage").RemoteEvents.GiveTool:FireServer(unpack(args))
end)
--// Teleports
Teleports:Button("House", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-36, 3, -200)
end)

Teleports:Button("Basement", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71, -15, -163)
end)

Teleports:Button("Attic", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-16, 35, -220)
end)

Teleports:Button("Store", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-422, 3, -121)
end)

Teleports:Button("Sewer", function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(129, 3, -125)
end)

Teleports:Button("Boss Room", function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-39, -287, -1480)
end)
