-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local menu = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TabsFrame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Tab1Button = Instance.new("ImageButton")
local Tab5Button = Instance.new("ImageButton")
local Tab2Button = Instance.new("ImageButton")
local PagesFrame = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Tab1Page = Instance.new("Frame")
local TracerToggle = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local GlowButton = Instance.new("TextButton")
local Colorwheel = Instance.new("Frame")
local ColourWheel = Instance.new("ImageButton")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Picker = Instance.new("ImageLabel")
local DarknessPicker = Instance.new("ImageButton")
local UIGradient = Instance.new("UIGradient")
local Slider = Instance.new("ImageLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local ColourDisplay = Instance.new("ImageLabel")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local Tab2Page = Instance.new("Frame")
local ToggleAimbot = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Tab5Page = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local ResetButton = Instance.new("TextButton")
local logo = Instance.new("ImageLabel")
local NotificationLabel = Instance.new("TextLabel")
local CheckMark = Instance.new("ImageLabel")
local Frame = Instance.new("Frame")
local TargetLabel = Instance.new("TextLabel")
local AdminLabel = Instance.new("TextLabel")
local ActiveBackground = Instance.new("Frame")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

menu.Name = "menu"
menu.Parent = ScreenGui
menu.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
menu.BorderColor3 = Color3.fromRGB(0, 0, 0)
menu.BorderSizePixel = 0
menu.Position = UDim2.new(0.221598268, 0, 0.0897975713, 0)
menu.Size = UDim2.new(0, 746, 0, 585)
menu.ZIndex = 2

UICorner.Parent = menu

TabsFrame.Name = "TabsFrame"
TabsFrame.Parent = menu
TabsFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TabsFrame.BackgroundTransparency = 1.000
TabsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabsFrame.BorderSizePixel = 0
TabsFrame.Position = UDim2.new(0, 0, 0.125258803, 0)
TabsFrame.Size = UDim2.new(0, 123, 0, 422)

UICorner_2.Parent = TabsFrame

Tab1Button.Name = "Tab1Button"
Tab1Button.Parent = TabsFrame
Tab1Button.BackgroundColor3 = Color3.fromRGB(0, 89, 255)
Tab1Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab1Button.BorderSizePixel = 0
Tab1Button.Position = UDim2.new(0.252032518, 0, 0.27251184, 0)
Tab1Button.Size = UDim2.new(0, 60, 0, 60)
Tab1Button.Image = "rbxassetid://113423029495967"

Tab5Button.Name = "Tab5Button"
Tab5Button.Parent = TabsFrame
Tab5Button.BackgroundColor3 = Color3.fromRGB(0, 89, 255)
Tab5Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab5Button.BorderSizePixel = 0
Tab5Button.Position = UDim2.new(0.252032518, 0, 0.447867304, 0)
Tab5Button.Size = UDim2.new(0, 60, 0, 60)
Tab5Button.Image = "rbxassetid://82597938767282"

Tab2Button.Name = "Tab2Button"
Tab2Button.Parent = TabsFrame
Tab2Button.BackgroundColor3 = Color3.fromRGB(0, 89, 255)
Tab2Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab2Button.BorderSizePixel = 0
Tab2Button.Position = UDim2.new(0.252032518, 0, 0.097156398, 0)
Tab2Button.Size = UDim2.new(0, 60, 0, 60)
Tab2Button.Image = "rbxassetid://124753543890133"

PagesFrame.Name = "PagesFrame"
PagesFrame.Parent = menu
PagesFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PagesFrame.BackgroundTransparency = 1.000
PagesFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
PagesFrame.BorderSizePixel = 0
PagesFrame.Position = UDim2.new(0.174468055, 0, 0.125258833, 0)
PagesFrame.Size = UDim2.new(0, 509, 0, 421)

UICorner_3.Parent = PagesFrame

Tab1Page.Name = "Tab1Page"
Tab1Page.Parent = PagesFrame
Tab1Page.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Tab1Page.BackgroundTransparency = 1.000
Tab1Page.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab1Page.BorderSizePixel = 0
Tab1Page.Position = UDim2.new(0.0301635973, 0, 0, 0)
Tab1Page.Size = UDim2.new(0, 493, 0, 422)

TracerToggle.Name = "TracerToggle"
TracerToggle.Parent = Tab1Page
TracerToggle.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
TracerToggle.BorderColor3 = Color3.fromRGB(53, 53, 53)
TracerToggle.Position = UDim2.new(0.0491136163, -50, 0.264647275, -25)
TracerToggle.Size = UDim2.new(0, 166, 0, 51)
TracerToggle.Font = Enum.Font.RobotoMono
TracerToggle.Text = "Tracers OFF"
TracerToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
TracerToggle.TextSize = 19.000

TextLabel.Parent = Tab1Page
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.257606477, 0, -0.116113745, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.Michroma
TextLabel.Text = "Visuals"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 24.000

GlowButton.Name = "GlowButton"
GlowButton.Parent = Tab1Page
GlowButton.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
GlowButton.BorderColor3 = Color3.fromRGB(53, 53, 53)
GlowButton.Position = UDim2.new(0.0491136163, -50, 0.0979863033, -25)
GlowButton.Size = UDim2.new(0, 166, 0, 51)
GlowButton.Font = Enum.Font.RobotoMono
GlowButton.Text = "glow"
GlowButton.TextColor3 = Color3.fromRGB(255, 255, 255)
GlowButton.TextSize = 19.000

Colorwheel.Name = "Colorwheel"
Colorwheel.Parent = Tab1Page
Colorwheel.BackgroundColor3 = Color3.fromRGB(13, 13, 13)
Colorwheel.BorderColor3 = Color3.fromRGB(0, 0, 0)
Colorwheel.BorderSizePixel = 0
Colorwheel.Position = UDim2.new(-2.61563396, 0, 5.04417753, 0)
Colorwheel.Size = UDim2.new(0, 214, 0, 206)

ColourWheel.Name = "ColourWheel"
ColourWheel.Parent = Colorwheel
ColourWheel.Active = false
ColourWheel.AnchorPoint = Vector2.new(0.5, 0.5)
ColourWheel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ColourWheel.BackgroundTransparency = 1.000
ColourWheel.BorderColor3 = Color3.fromRGB(27, 42, 53)
ColourWheel.BorderSizePixel = 0
ColourWheel.Position = UDim2.new(0.396839708, 0, 0.486896545, 0)
ColourWheel.Selectable = false
ColourWheel.Size = UDim2.new(0.906303763, 0, 0.697307706, 0)
ColourWheel.Image = "http://www.roblox.com/asset/?id=6020299385"

UIAspectRatioConstraint.Parent = ColourWheel
UIAspectRatioConstraint.AspectRatio = 1.000

Picker.Name = "Picker"
Picker.Parent = ColourWheel
Picker.AnchorPoint = Vector2.new(0.5, 0.5)
Picker.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Picker.BackgroundTransparency = 1.000
Picker.BorderColor3 = Color3.fromRGB(27, 42, 53)
Picker.BorderSizePixel = 0
Picker.Position = UDim2.new(0.5, 0, 0.5, 0)
Picker.Size = UDim2.new(0.0900257826, 0, 0.0900257975, 0)
Picker.Image = "http://www.roblox.com/asset/?id=3678860011"

DarknessPicker.Name = "DarknessPicker"
DarknessPicker.Parent = Colorwheel
DarknessPicker.Active = false
DarknessPicker.AnchorPoint = Vector2.new(0.5, 0.5)
DarknessPicker.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DarknessPicker.BackgroundTransparency = 1.000
DarknessPicker.BorderColor3 = Color3.fromRGB(27, 42, 53)
DarknessPicker.BorderSizePixel = 0
DarknessPicker.Position = UDim2.new(0.889578819, 0, 0.494262695, 0)
DarknessPicker.Selectable = false
DarknessPicker.Size = UDim2.new(0.20614785, 0, 1.00775146, 0)
DarknessPicker.ZIndex = 2
DarknessPicker.Image = "rbxassetid://3570695787"
DarknessPicker.ScaleType = Enum.ScaleType.Slice
DarknessPicker.SliceCenter = Rect.new(100, 100, 100, 100)
DarknessPicker.SliceScale = 0.120

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Rotation = 90
UIGradient.Parent = DarknessPicker

Slider.Name = "Slider"
Slider.Parent = DarknessPicker
Slider.AnchorPoint = Vector2.new(0.5, 0.5)
Slider.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Slider.BackgroundTransparency = 1.000
Slider.BorderColor3 = Color3.fromRGB(27, 42, 53)
Slider.BorderSizePixel = 0
Slider.Position = UDim2.new(0.491197795, 0, 0.0733607039, 0)
Slider.Size = UDim2.new(1.28656352, 0, 0.0265010502, 0)
Slider.ZIndex = 2
Slider.Image = "rbxassetid://3570695787"
Slider.ImageColor3 = Color3.fromRGB(255, 74, 74)
Slider.ScaleType = Enum.ScaleType.Slice
Slider.SliceCenter = Rect.new(100, 100, 100, 100)
Slider.SliceScale = 0.120

UIAspectRatioConstraint_2.Parent = DarknessPicker
UIAspectRatioConstraint_2.AspectRatio = 0.157

ColourDisplay.Name = "ColourDisplay"
ColourDisplay.Parent = Colorwheel
ColourDisplay.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ColourDisplay.BackgroundTransparency = 1.000
ColourDisplay.BorderColor3 = Color3.fromRGB(27, 42, 53)
ColourDisplay.BorderSizePixel = 0
ColourDisplay.Position = UDim2.new(0.299192339, 0, -0.451456308, 0)
ColourDisplay.Size = UDim2.new(0.535464764, 0, 0.411985368, 0)
ColourDisplay.ZIndex = 2
ColourDisplay.Image = "rbxassetid://3570695787"
ColourDisplay.ScaleType = Enum.ScaleType.Slice
ColourDisplay.SliceCenter = Rect.new(100, 100, 100, 100)
ColourDisplay.SliceScale = 0.120

UIAspectRatioConstraint_3.Parent = ColourDisplay

Tab2Page.Name = "Tab2Page"
Tab2Page.Parent = PagesFrame
Tab2Page.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Tab2Page.BackgroundTransparency = 1.000
Tab2Page.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab2Page.BorderSizePixel = 0
Tab2Page.Position = UDim2.new(0.0384408757, 0, 0, 0)
Tab2Page.Size = UDim2.new(0, 489, 0, 422)
Tab2Page.Visible = false

ToggleAimbot.Name = "Toggle Aimbot"
ToggleAimbot.Parent = Tab2Page
ToggleAimbot.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
ToggleAimbot.BorderColor3 = Color3.fromRGB(53, 53, 53)
ToggleAimbot.Position = UDim2.new(0.0465709493, -50, 0.126804233, -25)
ToggleAimbot.Size = UDim2.new(0, 140, 0, 52)
ToggleAimbot.Font = Enum.Font.RobotoMono
ToggleAimbot.Text = "Aimbot"
ToggleAimbot.TextColor3 = Color3.fromRGB(255, 255, 255)
ToggleAimbot.TextSize = 19.000

TextLabel_2.Parent = Tab2Page
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.25147146, 0, -0.116113745, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.Michroma
TextLabel_2.Text = "Combat"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 24.000

Tab5Page.Name = "Tab5Page"
Tab5Page.Parent = PagesFrame
Tab5Page.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Tab5Page.BackgroundTransparency = 1.000
Tab5Page.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tab5Page.BorderSizePixel = 0
Tab5Page.Size = UDim2.new(0, 509, 0, 422)
Tab5Page.Visible = false

TextLabel_3.Parent = Tab5Page
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.279217482, 0, -0.116113745, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 50)
TextLabel_3.Font = Enum.Font.Michroma
TextLabel_3.Text = "Character"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 24.000

ResetButton.Name = "ResetButton"
ResetButton.Parent = Tab5Page
ResetButton.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
ResetButton.BorderColor3 = Color3.fromRGB(53, 53, 53)
ResetButton.Position = UDim2.new(0.0815932155, -50, 0.0966020226, -25)
ResetButton.Size = UDim2.new(0, 162, 0, 51)
ResetButton.Font = Enum.Font.RobotoMono
ResetButton.Text = "Suicide"
ResetButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ResetButton.TextSize = 19.000

logo.Name = "logo"
logo.Parent = menu
logo.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
logo.BackgroundTransparency = 1.000
logo.BorderColor3 = Color3.fromRGB(0, 0, 0)
logo.BorderSizePixel = 0
logo.Position = UDim2.new(0.0281501338, 0, 0.0170940179, 0)
logo.Rotation = 15.000
logo.Size = UDim2.new(0, 80, 0, 80)
logo.Image = "rbxassetid://120338646628677"

NotificationLabel.Name = "NotificationLabel"
NotificationLabel.Parent = ScreenGui
NotificationLabel.Active = true
NotificationLabel.BackgroundColor3 = Color3.fromRGB(36, 77, 41)
NotificationLabel.BackgroundTransparency = 1.000
NotificationLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
NotificationLabel.BorderSizePixel = 0
NotificationLabel.Position = UDim2.new(0.79243046, 0, 0.255768955, 0)
NotificationLabel.Size = UDim2.new(0, 304, 0, 44)
NotificationLabel.Visible = false
NotificationLabel.Font = Enum.Font.Code
NotificationLabel.Text = "    Enabled function: NoClip"
NotificationLabel.TextColor3 = Color3.fromRGB(33, 255, 17)
NotificationLabel.TextSize = 15.000
NotificationLabel.TextTransparency = 1.000
NotificationLabel.TextWrapped = true

CheckMark.Name = "CheckMark"
CheckMark.Parent = NotificationLabel
CheckMark.Active = true
CheckMark.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CheckMark.BackgroundTransparency = 1.000
CheckMark.BorderColor3 = Color3.fromRGB(0, 0, 0)
CheckMark.BorderSizePixel = 0
CheckMark.Position = UDim2.new(0.0218524225, 0, 0.0540549532, 0)
CheckMark.Size = UDim2.new(0, 45, 0, 41)
CheckMark.Image = "rbxassetid://85837052454915"

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.00180018006, 0, -0.138888896, 0)
Frame.Size = UDim2.new(0, 1109, 0, 761)

TargetLabel.Name = "TargetLabel"
TargetLabel.Parent = ScreenGui
TargetLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TargetLabel.BackgroundTransparency = 1.000
TargetLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TargetLabel.BorderSizePixel = 0
TargetLabel.Position = UDim2.new(0.409540951, 0, 0.666666687, 0)
TargetLabel.Size = UDim2.new(0, 200, 0, 50)
TargetLabel.ZIndex = 10
TargetLabel.Font = Enum.Font.Gotham
TargetLabel.Text = ""
TargetLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TargetLabel.TextSize = 19.000

AdminLabel.Name = "AdminLabel"
AdminLabel.Parent = ScreenGui
AdminLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AdminLabel.BackgroundTransparency = 1.000
AdminLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
AdminLabel.BorderSizePixel = 0
AdminLabel.Position = UDim2.new(0.118718594, 0, 0.830246925, 0)
AdminLabel.Size = UDim2.new(0, 200, 0, 50)
AdminLabel.Visible = false
AdminLabel.Font = Enum.Font.Code
AdminLabel.Text = ""
AdminLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
AdminLabel.TextSize = 14.000

ActiveBackground.Name = "ActiveBackground"
ActiveBackground.Parent = ScreenGui
ActiveBackground.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ActiveBackground.BackgroundTransparency = 1.000
ActiveBackground.BorderColor3 = Color3.fromRGB(0, 0, 0)
ActiveBackground.BorderSizePixel = 0
ActiveBackground.Position = UDim2.new(-1.031407, 0, -0.827972114, 0)
ActiveBackground.Size = UDim2.new(0, 3745, 0, 1623)

-- Scripts:

local function GLUZI_fake_script() -- TracerToggle.LocalScript 
	local script = Instance.new('LocalScript', TracerToggle)

	-- LocalScript внутри TracerToggle
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local Camera = workspace.CurrentCamera
	local LocalPlayer = Players.LocalPlayer
	
	local tracers = {}
	local tracersEnabled = false
	
	-- Настройки
	local tracerColor = Color3.fromRGB(255, 0, 0)
	local tracerThickness = 1
	local fromScreenBottom = true
	
	-- Очистка всех трейсеров
	local function clearTracers()
		for _, tracer in pairs(tracers) do
			if tracer then
				tracer:Remove()
			end
		end
		table.clear(tracers)
	end
	
	-- Обновление кнопки
	local function updateButton()
		button.Text = tracersEnabled and "Tracers ON" or "Tracers OFF"
	end
	
	-- Главный цикл трейсеров
	RunService.RenderStepped:Connect(function()
		if not tracersEnabled then
			clearTracers()
			return
		end
	
		clearTracers()
	
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= LocalPlayer and player.Character and player.Character:FindFirstChild("HumanoidRootPart") then
				local hrp = player.Character.HumanoidRootPart
				local screenPos, onScreen = Camera:WorldToViewportPoint(hrp.Position)
	
				if onScreen then
					local tracer = Drawing.new("Line")
					tracer.Color = tracerColor
					tracer.Thickness = tracerThickness
					tracer.Transparency = 1
					tracer.Visible = true
	
					if fromScreenBottom then
						tracer.From = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y)
					else
						tracer.From = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
					end
	
					tracer.To = Vector2.new(screenPos.X, screenPos.Y)
					table.insert(tracers, tracer)
				end
			end
		end
	end)
	
	-- Обработка нажатия кнопки
	button.MouseButton1Click:Connect(function()
		tracersEnabled = not tracersEnabled
		updateButton()
	end)
	
	-- Инициализация
	updateButton()
	
end
coroutine.wrap(GLUZI_fake_script)()
local function UDXUWW_fake_script() -- GlowButton.LocalScript 
	local script = Instance.new('LocalScript', GlowButton)

	-- LocalScript, поместите внутрь вашей GUI‑кнопки GlowButton
	
	local button       = script.Parent
	local Players      = game:GetService("Players")
	local TweenService = game:GetService("TweenService")
	local LocalPlayer  = Players.LocalPlayer
	
	local isOn         = false
	local runningTask  = nil
	local colorUpdateTask = nil
	local connection   = nil
	
	-- Устанавливаем начальный текст кнопки
	button.Text = "Glow OFF"
	
	-- Получаем фрейм "Color" и ColorPreview внутри него
	local colorFrame = button:FindFirstChild("Color")
	local colorPreview = colorFrame and colorFrame:FindFirstChild("ColorPreview")
	
	if colorFrame then
		colorFrame.Visible = false
		colorFrame.BackgroundTransparency = 1
	end
	
	-- Удалить все Highlight‑эффекты
	local function removeAllGlow()
		for _, player in ipairs(Players:GetPlayers()) do
			if player.Character then
				local existing = player.Character:FindFirstChild("HighlightESP")
				if existing then
					existing:Destroy()
				end
			end
		end
	end
	
	-- Создать Highlight/Glow на персонаже
	local function createGlow(character)
		if not character or not character:FindFirstChild("HumanoidRootPart") then return end
		if character:FindFirstChild("HighlightESP") then return end
	
		local highlight = Instance.new("Highlight")
		highlight.Name                = "HighlightESP"
		highlight.Adornee             = character
		highlight.FillTransparency    = 1
		highlight.OutlineTransparency = 0
		highlight.DepthMode           = Enum.HighlightDepthMode.AlwaysOnTop
	
		if colorPreview then
			highlight.OutlineColor = colorPreview.BackgroundColor3
		end
	
		highlight.Parent = character
		return highlight
	end
	
	-- Обновить всем игрокам
	local function updateAllPlayers()
		for _, player in ipairs(Players:GetPlayers()) do
			if player ~= LocalPlayer and player.Character then
				createGlow(player.Character)
			end
		end
	end
	
	-- Обновить цвета у всех Glow
	local function updateAllGlowColors()
		if not colorPreview then return end
		for _, player in ipairs(Players:GetPlayers()) do
			if player ~= LocalPlayer and player.Character then
				local esp = player.Character:FindFirstChild("HighlightESP")
				if esp then
					esp.OutlineColor = colorPreview.BackgroundColor3
				end
			end
		end
	end
	
	-- Обработка нажатия кнопки
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
		button.Text = isOn and "Glow ON" or "Glow OFF"
	
		if isOn then
			updateAllPlayers()
	
			connection = Players.PlayerAdded:Connect(function(player)
				player.CharacterAdded:Connect(function(char)
					task.wait(1)
					if isOn then
						createGlow(char)
					end
				end)
			end)
	
			runningTask = task.spawn(function()
				while isOn do
					updateAllPlayers()
					task.wait(2)
				end
			end)
	
			colorUpdateTask = task.spawn(function()
				while isOn do
					updateAllGlowColors()
					task.wait(0.2)
				end
			end)
	
			if colorFrame then
				colorFrame.Visible = true
				TweenService:Create(colorFrame, TweenInfo.new(0.5), {BackgroundTransparency = 0}):Play()
			end
	
		else
			if connection then
				connection:Disconnect()
				connection = nil
			end
			if runningTask then
				task.cancel(runningTask)
				runningTask = nil
			end
			if colorUpdateTask then
				task.cancel(colorUpdateTask)
				colorUpdateTask = nil
			end
			removeAllGlow()
	
			if colorFrame then
				local tween = TweenService:Create(colorFrame, TweenInfo.new(0.5), {BackgroundTransparency = 1})
				tween:Play()
				tween.Completed:Connect(function()
					if not isOn then
						colorFrame.Visible = false
					end
				end)
			end
		end
	end)
	
end
coroutine.wrap(UDXUWW_fake_script)()
local function NZUXKBK_fake_script() -- Colorwheel.ColourWheelHandler 
	local script = Instance.new('LocalScript', Colorwheel)

	local colourWheel = script.Parent:WaitForChild("ColourWheel")
	local wheelPicker = colourWheel:WaitForChild("Picker")
	
	local darknessPicker = script.Parent:WaitForChild("DarknessPicker")
	local darknessSlider = darknessPicker:WaitForChild("Slider")
	
	local colourDisplay = script.Parent:WaitForChild("ColourDisplay")
	
	
	local uis = game:GetService("UserInputService")
	
	
	local buttonDown = false
	local movingSlider = false
	
	
	local function updateColour(centreOfWheel)
		
		
		local colourPickerCentre = Vector2.new(
			colourWheel.Picker.AbsolutePosition.X + (colourWheel.Picker.AbsoluteSize.X/2),
			colourWheel.Picker.AbsolutePosition.Y + (colourWheel.Picker.AbsoluteSize.Y/2)
		)
		local h = (math.pi - math.atan2(colourPickerCentre.Y - centreOfWheel.Y, colourPickerCentre.X - centreOfWheel.X)) / (math.pi * 2)
		
		local s = (centreOfWheel - colourPickerCentre).Magnitude / (colourWheel.AbsoluteSize.X/2)
		
		local v = math.abs((darknessSlider.AbsolutePosition.Y - darknessPicker.AbsolutePosition.Y) / darknessPicker.AbsoluteSize.Y - 1)
		
		
		local hsv = Color3.fromHSV(math.clamp(h, 0, 1), math.clamp(s, 0, 1), math.clamp(v, 0, 1))
		
		
		colourDisplay.ImageColor3 = hsv
		darknessPicker.UIGradient.Color = ColorSequence.new{
			ColorSequenceKeypoint.new(0, hsv), 
			ColorSequenceKeypoint.new(1, Color3.new(0, 0, 0))
		}
	end
	
	
	colourWheel.MouseButton1Down:Connect(function()
		buttonDown = true
	end)
	
	darknessPicker.MouseButton1Down:Connect(function()
		movingSlider = true
	end)
	
	
	uis.InputEnded:Connect(function(input)
		
		if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
		
		buttonDown = false
		movingSlider = false
	end)
	
	
	uis.InputChanged:Connect(function(input)
		
		if input.UserInputType ~= Enum.UserInputType.MouseMovement then return end
		
		
		local mousePos = uis:GetMouseLocation() - Vector2.new(0, game:GetService("GuiService"):GetGuiInset().Y)
		
		local centreOfWheel = Vector2.new(colourWheel.AbsolutePosition.X + (colourWheel.AbsoluteSize.X/2), colourWheel.AbsolutePosition.Y + (colourWheel.AbsoluteSize.Y/2))
		
		local distanceFromWheel = (mousePos - centreOfWheel).Magnitude
		
		
		if distanceFromWheel <= colourWheel.AbsoluteSize.X/2 and buttonDown then
			
			wheelPicker.Position = UDim2.new(0, mousePos.X - colourWheel.AbsolutePosition.X, 0, mousePos.Y - colourWheel.AbsolutePosition.Y)
	
			
		elseif movingSlider then
			
			darknessSlider.Position = UDim2.new(darknessSlider.Position.X.Scale, 0, 0, 
				math.clamp(
				mousePos.Y - darknessPicker.AbsolutePosition.Y, 
				0, 
				darknessPicker.AbsoluteSize.Y)
			)	
		end
		
		
		updateColour(centreOfWheel)
	end)
end
coroutine.wrap(NZUXKBK_fake_script)()
local function EZDOTW_fake_script() -- ToggleAimbot.LocalScript 
	local script = Instance.new('LocalScript', ToggleAimbot)

	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local LocalPlayer = Players.LocalPlayer
	local Camera = workspace.CurrentCamera
	
	local gui = LocalPlayer:WaitForChild("PlayerGui"):WaitForChild("ScreenGui")
	local button = gui:WaitForChild("AimbotToggleButton") -- Название твоей кнопки в GUI
	
	local Aimbot = {
		Enabled = false,
		HitPart = "Head",
		Prediction = 0.2,
		AutoShoot = true,
	}
	
	local Target = nil
	
	local function GetClosestTarget()
		local Mouse = LocalPlayer:GetMouse()
		local closestDistance = math.huge
		local closestPlayer = nil
	
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= LocalPlayer and player.Character and player.Character:FindFirstChild(Aimbot.HitPart) then
				local head = player.Character[Aimbot.HitPart]
				local screenPos, onScreen = Camera:WorldToScreenPoint(head.Position)
				if onScreen then
					local dist = (Vector2.new(Mouse.X, Mouse.Y) - Vector2.new(screenPos.X, screenPos.Y)).Magnitude
					if dist < closestDistance then
						closestDistance = dist
						closestPlayer = player
					end
				end
			end
		end
	
		return closestPlayer
	end
	
	button.Text = "Aimbot OFF"
	
	button.MouseButton1Click:Connect(function()
		Aimbot.Enabled = not Aimbot.Enabled
		button.Text = Aimbot.Enabled and "Aimbot ON" or "Aimbot OFF"
		if not Aimbot.Enabled then
			Target = nil
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if not Aimbot.Enabled then return end
	
		if not Target then
			Target = GetClosestTarget()
		end
	
		if Target and Target.Character and Target.Character:FindFirstChild(Aimbot.HitPart) then
			local head = Target.Character[Aimbot.HitPart]
			local predictedPos = head.Position + head.Velocity * Aimbot.Prediction
			Camera.CFrame = CFrame.new(Camera.CFrame.Position, predictedPos)
	
			if Aimbot.AutoShoot then
				-- Автострельба (только если нужно)
				mouse1press()
				task.wait(0.01)
				mouse1release()
			end
		else
			Target = nil
		end
	end)
	
end
coroutine.wrap(EZDOTW_fake_script)()
local function TMTB_fake_script() -- ResetButton.reset 
	local script = Instance.new('LocalScript', ResetButton)

	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local button = script.Parent
	
	-- Функция суицида с мгновенным переходом в "dead" (как будто добили в Da Hood)
	local function instantDeathDaHood()
		local character = player.Character
		if not character then return end
	
		local humanoid = character:FindFirstChildOfClass("Humanoid")
		local hrp = character:FindFirstChild("HumanoidRootPart")
	
		-- Установка состояния "Knocked" и принудительное убийство
		if humanoid and hrp then
			-- Попытка установить нокдаун анимации, как у добитого
			local Knocked = character:FindFirstChild("BodyEffects") and character.BodyEffects:FindFirstChild("K.O") 
			if Knocked and Knocked:IsA("BoolValue") then
				Knocked.Value = true
			end
	
			-- Также включим "Break" и "Dead" если есть
			local Dead = character:FindFirstChild("BodyEffects") and character.BodyEffects:FindFirstChild("Dead")
			if Dead and Dead:IsA("BoolValue") then
				Dead.Value = true
			end
	
			local Break = character:FindFirstChild("BodyEffects") and character.BodyEffects:FindFirstChild("Break")
			if Break and Break:IsA("BoolValue") then
				Break.Value = true
			end
	
			-- Принудительно обнуляем здоровье
			humanoid.Health = 0
		end
	end
	
	-- Обработка нажатия кнопки
	button.MouseButton1Click:Connect(function()
		instantDeathDaHood()
	end)
	
	-- Название кнопки
	button.Text = "Suicide"
	
end
coroutine.wrap(TMTB_fake_script)()
local function OAPOP_fake_script() -- ScreenGui.Tabs 
	local script = Instance.new('LocalScript', ScreenGui)

	local TweenService = game:GetService("TweenService")
	local UserInputService = game:GetService("UserInputService")
	local Lighting = game:GetService("Lighting")
	local Players = game:GetService("Players")
	
	local playerGui = Players.LocalPlayer:WaitForChild("PlayerGui")
	local screenGui = script.Parent
	
	local menu = screenGui:WaitForChild("menu")
	local tabsFrame = menu:WaitForChild("TabsFrame")
	local pagesFrame = menu:WaitForChild("PagesFrame")
	local logo = menu:FindFirstChild("logo")
	
	
	local blur = Instance.new("BlurEffect")
	blur.Size = 0
	blur.Parent = Lighting
	
	local backgroundDim = Instance.new("Frame")
	backgroundDim.Name = "BackgroundDim"
	backgroundDim.Size = UDim2.new(1, 0, 1, 0)
	backgroundDim.Position = UDim2.new(0, 0, 0, 0)
	backgroundDim.BackgroundColor3 = Color3.new(0, 0, 0)
	backgroundDim.BackgroundTransparency = 1
	backgroundDim.ZIndex = 5
	backgroundDim.BorderSizePixel = 0
	backgroundDim.Visible = false
	backgroundDim.Parent = playerGui
	
	local tweenInfoOpen = TweenInfo.new(0.35, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	local tweenInfo = TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	
	local originalMenuPosition = menu.Position
	local hiddenMenuPosition = originalMenuPosition + UDim2.new(0, 0, 0.05, 0)
	
	menu.Position = hiddenMenuPosition
	menu.BackgroundTransparency = 1
	menu.Visible = false
	pagesFrame.Visible = false
	pagesFrame.BackgroundTransparency = 1
	
	local pages = {}
	for _, child in ipairs(pagesFrame:GetChildren()) do
		if child:IsA("Frame") then
			pages[child.Name] = child
			child.Visible = false
		end
	end
	
	local buttonToPageMap = {
		Tab1Button = "Tab1Page",
		Tab2Button = "Tab2Page",
		Tab3Button = "Tab3Page",
		Tab4Button = "Tab4Page",
		Tab5Button = "Tab5Page",
		Tab6Button = "Tab6Page",
		Tab7Button = "Tab7Page",
		Tab8Button = "Tab8Page",
		Tab9Button = "Tab9Page",
		Tab10Button = "Tab10Page",
	}
	
	local currentPage = nil
	local currentButton = nil
	local isAnimating = false
	
	local function tweenButtonTransparency(button, bgTransparency, imgTransparency, duration)
		TweenService:Create(button, TweenInfo.new(duration), {BackgroundTransparency = bgTransparency}):Play()
		for _, child in ipairs(button:GetChildren()) do
			if child:IsA("ImageLabel") or child:IsA("ImageButton") then
				TweenService:Create(child, TweenInfo.new(duration), {ImageTransparency = imgTransparency}):Play()
			end
		end
	end
	
	local function highlightButton(buttonToHighlight)
		for _, button in ipairs(tabsFrame:GetChildren()) do
			if button:IsA("ImageButton") then
				if button == buttonToHighlight then
					tweenButtonTransparency(button, 0, 0, tweenInfo.Time)
				else
					tweenButtonTransparency(button, 1, 1, tweenInfo.Time)
				end
			end
		end
	end
	
	local function tweenTabsFrameTransparency(targetBgTransparency, targetImgTransparency, duration)
		for _, button in ipairs(tabsFrame:GetChildren()) do
			if button:IsA("ImageButton") then
				tweenButtonTransparency(button, targetBgTransparency, targetImgTransparency, duration)
			end
		end
	end
	
	local function tweenMenuContentTransparency(targetTransparency, duration)
		TweenService:Create(menu, TweenInfo.new(duration), {BackgroundTransparency = targetTransparency}):Play()
		tweenTabsFrameTransparency(targetTransparency, targetTransparency, duration)
	
		if currentPage then
			for _, desc in ipairs(currentPage:GetDescendants()) do
				if desc:IsA("TextButton") or desc:IsA("TextLabel") then
					TweenService:Create(desc, TweenInfo.new(duration), {TextTransparency = targetTransparency}):Play()
				elseif desc:IsA("ImageLabel") or desc:IsA("ImageButton") then
					TweenService:Create(desc, TweenInfo.new(duration), {ImageTransparency = targetTransparency}):Play()
				end
				if desc:IsA("GuiObject") then
					TweenService:Create(desc, TweenInfo.new(duration), {BackgroundTransparency = targetTransparency}):Play()
				end
			end
		end
	
		if logo and logo:IsA("ImageLabel") then
			TweenService:Create(logo, TweenInfo.new(duration), {ImageTransparency = targetTransparency}):Play()
		end
	end
	
	local function tweenDescendantsTransparencyAndPosition(frame, transparencyTarget, positionOffset, duration)
		for _, desc in ipairs(frame:GetDescendants()) do
			local tweenProps = {}
	
			if desc:IsA("TextLabel") or desc:IsA("TextButton") then
				tweenProps.TextTransparency = transparencyTarget
				tweenProps.BackgroundTransparency = transparencyTarget
			elseif desc:IsA("ImageLabel") or desc:IsA("ImageButton") then
				tweenProps.ImageTransparency = transparencyTarget
				tweenProps.BackgroundTransparency = transparencyTarget
			end
	
			if positionOffset and desc.Parent == frame then
				if desc:IsA("GuiObject") then
					local newPos = desc.Position + positionOffset
					TweenService:Create(desc, TweenInfo.new(duration), {Position = newPos}):Play()
				end
			end
	
			if next(tweenProps) then
				TweenService:Create(desc, TweenInfo.new(duration), tweenProps):Play()
			end
		end
	end
	
	local function showPage(pageName, button)
		if isAnimating then return end
		local newPage = pages[pageName]
		if not newPage then return end
		if currentPage == newPage then return end
	
		isAnimating = true
	
		if currentPage then
			tweenDescendantsTransparencyAndPosition(currentPage, 1, UDim2.new(0,0,0.05,0), tweenInfo.Time)
			wait(tweenInfo.Time)
			currentPage.Visible = false
			for _, desc in ipairs(currentPage:GetChildren()) do
				if desc:IsA("GuiObject") then
					desc.Position = desc.Position - UDim2.new(0,0,0.05,0)
				end
			end
		end
	
		highlightButton(button)
	
		newPage.Visible = true
		for _, desc in ipairs(newPage:GetChildren()) do
			if desc:IsA("GuiObject") then
				desc.Position = desc.Position - UDim2.new(0, 0, 0.05, 0)
			end
		end
		tweenDescendantsTransparencyAndPosition(newPage, 0, UDim2.new(0,0,0.05,0), tweenInfo.Time)
	
		currentPage = newPage
		currentButton = button
	
		wait(tweenInfo.Time)
		isAnimating = false
	end
	
	local function openMenu()
		if isAnimating then return end
		isAnimating = true
	
		backgroundDim.Visible = true
		TweenService:Create(backgroundDim, tweenInfoOpen, {BackgroundTransparency = 0.75}):Play()
		TweenService:Create(blur, tweenInfoOpen, {Size = 24}):Play()
	
		menu.Visible = true
		menu.Position = originalMenuPosition
		menu.BackgroundTransparency = 0
	
		pagesFrame.Visible = true
		pagesFrame.BackgroundTransparency = 0
	
		if not currentButton then
			currentButton = tabsFrame:FindFirstChild("Tab1Button")
		end
	
		tweenMenuContentTransparency(0, tweenInfoOpen.Time)
		showPage("Tab1Page", currentButton)
	
		wait(tweenInfoOpen.Time)
		isAnimating = false
	end
	
	local function closeMenu()
		if isAnimating then return end
		isAnimating = true
	
		tweenMenuContentTransparency(1, tweenInfo.Time)
		TweenService:Create(pagesFrame, tweenInfo, {BackgroundTransparency = 1}):Play()
		TweenService:Create(backgroundDim, tweenInfo, {BackgroundTransparency = 1}):Play()
		TweenService:Create(blur, tweenInfo, {Size = 0}):Play()
	
		TweenService:Create(menu, tweenInfo, {BackgroundTransparency = 1}):Play()
	
		task.delay(tweenInfo.Time, function()
			pagesFrame.Visible = false
			menu.Visible = false
			backgroundDim.Visible = false
			isAnimating = false
		end)
	end
	
	for _, button in ipairs(tabsFrame:GetChildren()) do
		if button:IsA("ImageButton") then
			local targetPage = buttonToPageMap[button.Name]
			if targetPage then
				if button.Name == "Tab1Button" then
					button.BackgroundTransparency = 0
					for _, child in ipairs(button:GetChildren()) do
						if child:IsA("ImageLabel") or child:IsA("ImageButton") then
							child.ImageTransparency = 0
						end
					end
					currentButton = button
				else
					button.BackgroundTransparency = 1
					for _, child in ipairs(button:GetChildren()) do
						if child:IsA("ImageLabel") or child:IsA("ImageButton") then
							child.ImageTransparency = 1
						end
					end
				end
				button.MouseButton1Click:Connect(function()
					showPage(targetPage, button)
				end)
			end
		end
	end
	
	UserInputService.InputBegan:Connect(function(input, gameProcessed)
		if gameProcessed then return end
		if input.KeyCode == Enum.KeyCode.P then
			if menu.Visible then
				closeMenu()
			else
				openMenu()
			end
		end
	end)
	
	
	showPage("Tab1Page", currentButton)
	
end
coroutine.wrap(OAPOP_fake_script)()
local function JTHQ_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	local screenGui = script.Parent
	local notifFrame = screenGui:WaitForChild("NotificationFrame")
	local notifLabel = notifFrame:WaitForChild("NotificationLabel")
	
	local function showNotification(text)
		notifLabel.Text = text
		notifLabel.Visible = true
		notifLabel.TextTransparency = 1
		notifLabel.BackgroundTransparency = 1
	
		for i = 1, 10 do
			notifLabel.TextTransparency = 1 - i * 0.1
			notifLabel.BackgroundTransparency = 1 - i * 0.05
			task.wait(0.03)
		end
	
		task.wait(3)
	
		for i = 1, 10 do
			notifLabel.TextTransparency = i * 0.1
			notifLabel.BackgroundTransparency = i * 0.05
			task.wait(0.03)
		end
	
		notifLabel.Visible = false
	end
	
	-- Проверка: уведомление по нажатию клавиши "G"
	game:GetService("UserInputService").InputBegan:Connect(function(input, gpe)
		if gpe then return end
		if input.KeyCode == Enum.KeyCode.G then
			showNotification("Тестовое уведомление!")
		end
	end)
	
end
coroutine.wrap(JTHQ_fake_script)()
local function KSQAY_fake_script() -- ScreenGui.Inject 
	local script = Instance.new('LocalScript', ScreenGui)

	local TweenService = game:GetService("TweenService")
	
	local screenGui = script.Parent
	local notificationLabel = screenGui:WaitForChild("NotificationLabel")
	local checkMark = notificationLabel:WaitForChild("CheckMark")
	
	notificationLabel.Size = UDim2.new(0, 264, 0, 44)
	
	local function fadeIn()
		notificationLabel.Visible = true
		notificationLabel.BackgroundTransparency = 1
		notificationLabel.TextTransparency = 1
		checkMark.ImageTransparency = 1
	
		local tweenInfo = TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	
		local bgTween = TweenService:Create(notificationLabel, tweenInfo, {BackgroundTransparency = 0})
		local textTween = TweenService:Create(notificationLabel, tweenInfo, {TextTransparency = 0})
		local checkMarkTween = TweenService:Create(checkMark, tweenInfo, {ImageTransparency = 0})
	
		bgTween:Play()
		textTween:Play()
		checkMarkTween:Play()
	
		bgTween.Completed:Wait()
	end
	
	local function fadeOut()
		local tweenInfo = TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	
		local bgTween = TweenService:Create(notificationLabel, tweenInfo, {BackgroundTransparency = 1})
		local textTween = TweenService:Create(notificationLabel, tweenInfo, {TextTransparency = 1})
		local checkMarkTween = TweenService:Create(checkMark, tweenInfo, {ImageTransparency = 1})
	
		bgTween:Play()
		textTween:Play()
		checkMarkTween:Play()
	
		bgTween.Completed:Wait()
		notificationLabel.Visible = false
	end
	
	-- Функция показа уведомления с нужным текстом
	local function showSuccessNotification()
		notificationLabel.Text = "   Successful Inject, Happy Cheating!"
		fadeIn()
		wait(3)
		fadeOut()
	end
	
	-- Вызов функции после успешной инъекции скрипта:
	showSuccessNotification()
	
end
coroutine.wrap(KSQAY_fake_script)()
