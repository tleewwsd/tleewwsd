local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Bear X Shark Hub", "Synapse")

local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Teleport")

Section:NewButton("Start Island", "Teleport", function()
    game.Players.LocalPlayers.Character.HumanoidRootPart.CFrame = CFrame.new()
end)
