-- Gui to Lua
-- Version: 3.2

-- Instances:

local Commands = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Frame_3 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local UIListLayout = Instance.new("UIListLayout")
local Frame_4 = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local Frame_5 = Instance.new("Frame")
local TextLabel_6 = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")

--Properties:

Commands.Name = "Commands"
Commands.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Commands.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Commands
Frame.BackgroundColor3 = Color3.fromRGB(74, 161, 255)
Frame.BorderColor3 = Color3.fromRGB(74, 161, 255)
Frame.Position = UDim2.new(0.525304317, 0, 0.122352935, 0)
Frame.Size = UDim2.new(0, 290, 0, 25)

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(74, 161, 255)
TextButton.BorderColor3 = Color3.fromRGB(74, 161, 255)
TextButton.Position = UDim2.new(0.91200012, 0, 0, 0)
TextButton.Size = UDim2.new(0, 25, 0, 24)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "_"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 14.000

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Frame_2.BorderColor3 = Color3.fromRGB(50, 50, 50)
Frame_2.Position = UDim2.new(0, 0, 0.937999964, 0)
Frame_2.Size = UDim2.new(0, 290, 0, 571)

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(74, 161, 255)
TextLabel.BorderColor3 = Color3.fromRGB(74, 161, 255)
TextLabel.Position = UDim2.new(0.153551728, 0, -0.086751312, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 40)
TextLabel.Font = Enum.Font.Cartoon
TextLabel.Text = "Commands"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 25.000

ScrollingFrame.Parent = Frame_2
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(51, 51, 51)
ScrollingFrame.Size = UDim2.new(0, 303, 0, 569)
ScrollingFrame.BottomImage = ""
ScrollingFrame.MidImage = ""
ScrollingFrame.TopImage = ""
ScrollingFrame.VerticalScrollBarInset = Enum.ScrollBarInset.Always

Frame_3.Parent = ScrollingFrame
Frame_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_3.BackgroundTransparency = 1.000
Frame_3.BorderColor3 = Color3.fromRGB(50, 50, 50)
Frame_3.Position = UDim2.new(0, 0, -0.00165221305, 0)
Frame_3.Size = UDim2.new(0, 289, 0, 63)

TextLabel_2.Parent = Frame_3
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(0, 147, 0, 39)
TextLabel_2.Font = Enum.Font.Cartoon
TextLabel_2.Text = ".fly"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 36.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_3.Parent = Frame_3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(-0.00346020772, 0, 0.619047642, 0)
TextLabel_3.Size = UDim2.new(0, 289, 0, 25)
TextLabel_3.Font = Enum.Font.Cartoon
TextLabel_3.Text = "Makes you fly easily"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 14.000
TextLabel_3.TextXAlignment = Enum.TextXAlignment.Left

UIListLayout.Parent = ScrollingFrame
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder

Frame_4.Parent = ScrollingFrame
Frame_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_4.BackgroundTransparency = 1.000
Frame_4.BorderColor3 = Color3.fromRGB(50, 50, 50)
Frame_4.Position = UDim2.new(0, 0, -0.00165221305, 0)
Frame_4.Size = UDim2.new(0, 289, 0, 63)

TextLabel_4.Parent = Frame_4
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Size = UDim2.new(0, 147, 0, 39)
TextLabel_4.Font = Enum.Font.Cartoon
TextLabel_4.Text = ".chat"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 36.000
TextLabel_4.TextWrapped = true
TextLabel_4.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_5.Parent = Frame_4
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(-0.00346020772, 0, 0.619047642, 0)
TextLabel_5.Size = UDim2.new(0, 289, 0, 28)
TextLabel_5.Font = Enum.Font.Cartoon
TextLabel_5.Text = "Makes you say something, if chatting was disabled ofc"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true
TextLabel_5.TextXAlignment = Enum.TextXAlignment.Left

Frame_5.Parent = ScrollingFrame
Frame_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_5.BackgroundTransparency = 1.000
Frame_5.BorderColor3 = Color3.fromRGB(50, 50, 50)
Frame_5.Position = UDim2.new(0, 0, -0.00165221305, 0)
Frame_5.Size = UDim2.new(0, 289, 0, 63)

TextLabel_6.Parent = Frame_5
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Size = UDim2.new(0, 147, 0, 39)
TextLabel_6.Font = Enum.Font.Cartoon
TextLabel_6.Text = ".spamchat"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextSize = 36.000
TextLabel_6.TextWrapped = true
TextLabel_6.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_7.Parent = Frame_5
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(-0.00346020772, 0, 0.619047642, 0)
TextLabel_7.Size = UDim2.new(0, 289, 0, 28)
TextLabel_7.Font = Enum.Font.Cartoon
TextLabel_7.Text = "Again, same thing but spams messages instead"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextSize = 14.000
TextLabel_7.TextWrapped = true
TextLabel_7.TextXAlignment = Enum.TextXAlignment.Left
