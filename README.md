-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Drag = Instance.new("Frame")
local Main = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local TextButton1 = Instance.new("TextButton")
local ImageButton = Instance.new("ImageButton")
local ImageButton1 = Instance.new("ImageButton")
local ImageButton2 = Instance.new("ImageButton")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel1 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Drag.Name = "Drag"
Drag.Parent = ScreenGui
Drag.BackgroundColor3 = Color3.fromRGB(0, 0, 127)
Drag.BorderColor3 = Color3.fromRGB(0, 0, 0)
Drag.BorderSizePixel = 0
Drag.Position = UDim2.new(0.169197395, 0, 0.24029851, 0)
Drag.Size = UDim2.new(0, 669, 0, 310)

Main.Name = "Main"
Main.Parent = Drag
Main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0, 0, 0.154838711, 0)
Main.Size = UDim2.new(0, 669, 0, 262)

TextBox.Parent = Main
TextBox.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0149476836, 0, 0.0419847332, 0)
TextBox.Size = UDim2.new(0, 649, 0, 192)
TextBox.Font = Enum.Font.Arcade
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 127)
TextBox.TextSize = 10.000
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0, 0, 0.874045789, 0)
TextButton.Size = UDim2.new(0, 93, 0, 33)
TextButton.Font = Enum.Font.Unknown
TextButton.Text = "Execute"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 127)
TextButton.TextSize = 10.000
TextButton.TextWrapped = true

TextButton1.Name = "TextButton1"
TextButton1.Parent = Main
TextButton1.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
TextButton1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.BorderSizePixel = 0
TextButton1.Position = UDim2.new(0.17339313, 0, 0.874045789, 0)
TextButton1.Size = UDim2.new(0, 93, 0, 33)
TextButton1.Font = Enum.Font.Unknown
TextButton1.Text = "Clear"
TextButton1.TextColor3 = Color3.fromRGB(0, 0, 127)
TextButton1.TextSize = 10.000
TextButton1.TextWrapped = true

ImageButton.Parent = Main
ImageButton.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.932735443, 0, 0.854961812, 0)
ImageButton.Size = UDim2.new(0, 45, 0, 38)
ImageButton.Image = "rbxassetid://78055725598932"

ImageButton1.Name = "ImageButton1"
ImageButton1.Parent = Main
ImageButton1.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
ImageButton1.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton1.BorderSizePixel = 0
ImageButton1.Position = UDim2.new(0.828101635, 0, 0.854961812, 0)
ImageButton1.Size = UDim2.new(0, 45, 0, 38)
ImageButton1.Image = "rbxassetid://93350268913116"

ImageButton2.Name = "ImageButton2"
ImageButton2.Parent = Main
ImageButton2.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
ImageButton2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton2.BorderSizePixel = 0
ImageButton2.Position = UDim2.new(0.729446948, 0, 0.854961812, 0)
ImageButton2.Size = UDim2.new(0, 45, 0, 38)
ImageButton2.Image = "rbxassetid://107464745333750"

ImageLabel.Parent = Drag
ImageLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 127)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 64, 0, 48)
ImageLabel.Image = "rbxassetid://119429876747959"

TextLabel.Parent = Drag
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.19730942, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 48)
TextLabel.Font = Enum.Font.Arcade
TextLabel.Text = "SabuzaV6"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 20.000

TextLabel1.Name = "TextLabel1"
TextLabel1.Parent = Drag
TextLabel1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel1.BackgroundTransparency = 1.000
TextLabel1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.BorderSizePixel = 0
TextLabel1.Position = UDim2.new(0.497757852, 0, 0, 0)
TextLabel1.Size = UDim2.new(0, 200, 0, 48)
TextLabel1.Font = Enum.Font.Arcade
TextLabel1.Text = "Private Edition"
TextLabel1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.TextSize = 19.000

-- Scripts:

local function USOSHC_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent
	local textbox = script.Parent.Parent.TextBox
	button.MouseButton1Click:Connect(function()
		loadstring(textbox.Text)()
	end)
end
coroutine.wrap(USOSHC_fake_script)()
local function UXWLR_fake_script() -- TextButton1.LocalScript 
	local script = Instance.new('LocalScript', TextButton1)

	local button = script.Parent
	local textbox = script.Parent.Parent.TextBox
	button.MouseButton1Click:Connect(function()
		textbox.Text = ""
	end)
end
coroutine.wrap(UXWLR_fake_script)()
local function RJCYQTT_fake_script() -- Drag.Dragify 
	local script = Instance.new('LocalScript', Drag)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
		dragToggle = nil
		dragSpeed = 0.15
		dragInput = nil
		dragStart = nil
		dragPos = nil
		function updateInput(input)
			Delta = input.Position - dragStart
			Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
			game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.15), {Position = Position}):Play()
		end
		Frame.InputBegan:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
				dragToggle = true
				dragStart = input.Position
				startPos = Frame.Position
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragToggle = false
					end
				end)
			end
		end)
		Frame.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if input == dragInput and dragToggle then
				updateInput(input)
			end
		end)
	end
	dragify(script.Parent)
	
end
coroutine.wrap(RJCYQTT_fake_script)()
