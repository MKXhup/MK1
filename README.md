--Made by !           Crying Banana Cat#8869 & invalid-user#6672

print("Made by !           Crying Banana Cat#8869 & invalid-user#6672")

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local title = Instance.new("TextLabel")
local tutorial = Instance.new("TextButton")
local autofarm = Instance.new("TextButton")
local close = Instance.new("TextButton")
local openmain = Instance.new("Frame")
local open = Instance.new("TextButton")
--Properties:
ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.new(0, 0, 0)
main.Position = UDim2.new(0.0203577988, 0, 0.641277611, 0)
main.Size = UDim2.new(0, 332, 0, 211)
main.Visible = true
main.Active = true
main.Draggable = true

title.Name = "title"
title.Parent = main
title.BackgroundColor3 = Color3.new(1, 0, 1)
title.Size = UDim2.new(0, 332, 0, 31)
title.Font = Enum.Font.GothamBold
title.Text = "Pet Sim X MK"
title.TextColor3 = Color3.new(0, 0, 0)
title.TextSize = 14

tutorial.Name = "tutorial"
tutorial.Parent = main
tutorial.BackgroundColor3 = Color3.new(0.333333, 1, 0)
tutorial.Position = UDim2.new(0.036144577, 0, 0.379146934, 0)
tutorial.Size = UDim2.new(0, 110, 0, 50)
tutorial.Font = Enum.Font.GothamBold
tutorial.Text = "Tutorial"
tutorial.TextColor3 = Color3.new(0, 0, 0)
tutorial.TextScaled = true
tutorial.TextSize = 10
tutorial.TextWrapped = true
tutorial.MouseButton1Down:connect(function()
print("alright kid, here.")
wait(1.5)
print("name all ur equipped pets in order as numbers, example: 1, 2, 3, 4 then click autofarm once all are renamed")
end)

autofarm.Name = "autofarm"
autofarm.Parent = main
autofarm.BackgroundColor3 = Color3.new(0.333333, 1, 0)
autofarm.Position = UDim2.new(0.614457846, 0, 0.379146934, 0)
autofarm.Size = UDim2.new(0, 110, 0, 50)
autofarm.Font = Enum.Font.GothamBold
autofarm.Text = "AutoFarm"
autofarm.TextColor3 = Color3.new(0, 0, 0)
autofarm.TextScaled = true
autofarm.TextSize = 14
autofarm.TextWrapped = true
autofarm.MouseButton1Down:connect(function()
print("Made by !           Crying Banana Cat#8869 & invalid-user#6672")
wait(0.5)
loadstring(game:HttpGet("https://pastebin.com/raw/3QtNAwjB", true))()
end)

close.Name = "close"
close.Parent = none
close.BackgroundColor3 = Color3.new(1, 0, 0)
close.Position = UDim2.new(0.879518092, 0, 0, 0)
close.Size = UDim2.new(0, 40, 0, 31)
close.Font = Enum.Font.GothamBlack
close.Text = "X"
close.TextColor3 = Color3.new(0, 0, 0)
close.TextScaled = true
close.TextSize = 14
close.TextWrapped = true
close.MouseButton1Down:connect(function()
main.Visible = true
openmain.Visible = false
end)

openmain.Name = "openmain"
openmain.Parent = none
openmain.BackgroundColor3 = Color3.new(1, 1, 1)
openmain.Position = UDim2.new(0.00801973976, 0, 0.423832953, 0)
openmain.Size = UDim2.new(0, 100, 0, 28)
openmain.Active = true
openmain.Draggable = true

open.Name = "open"
open.Parent = openmain
open.BackgroundColor3 = Color3.new(1, 0, 0)
open.Size = UDim2.new(0, 100, 0, 28)
open.Font = Enum.Font.GothamBold
open.Text = "OPEN"
open.TextColor3 = Color3.new(0, 0, 0)
open.TextSize = 18
open.TextWrapped = true
open.MouseButton1Down:connect(function()
openmain.Visible = false
main.Visible = true
end)
