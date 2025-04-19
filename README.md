-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Skybox = Instance.new("TextButton")
local Decal = Instance.new("TextButton")
local Theme = Instance.new("TextButton")
local Disco = Instance.new("TextButton")
local Theme2 = Instance.new("TextButton")
local SteveSpam = Instance.new("TextButton")
local Frame1 = Instance.new("Frame")
local Frame2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_2_2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.246509597, 0, 0.406434625, 0)
Frame.Size = UDim2.new(0, 466, 0, 154)

Skybox.Name = "Skybox"
Skybox.Parent = Frame
Skybox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Skybox.BorderColor3 = Color3.fromRGB(0, 0, 0)
Skybox.BorderSizePixel = 0
Skybox.Position = UDim2.new(0.0214592274, 0, 0.0830039531, 0)
Skybox.Size = UDim2.new(0, 135, 0, 50)
Skybox.Font = Enum.Font.Arcade
Skybox.Text = "Skybox"
Skybox.TextColor3 = Color3.fromRGB(255, 255, 255)
Skybox.TextSize = 14.000

Decal.Name = "Decal"
Decal.Parent = Frame
Decal.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Decal.BorderColor3 = Color3.fromRGB(0, 0, 0)
Decal.BorderSizePixel = 0
Decal.Position = UDim2.new(0.35407725, 0, 0.0830039531, 0)
Decal.Size = UDim2.new(0, 135, 0, 50)
Decal.Font = Enum.Font.Arcade
Decal.Text = "Decal"
Decal.TextColor3 = Color3.fromRGB(255, 255, 255)
Decal.TextSize = 14.000

Theme.Name = "Theme"
Theme.Parent = Frame
Theme.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Theme.BorderColor3 = Color3.fromRGB(0, 0, 0)
Theme.BorderSizePixel = 0
Theme.Position = UDim2.new(0.693133056, 0, 0.0830039531, 0)
Theme.Size = UDim2.new(0, 135, 0, 50)
Theme.Font = Enum.Font.Arcade
Theme.Text = "Theme"
Theme.TextColor3 = Color3.fromRGB(255, 255, 255)
Theme.TextSize = 14.000

Disco.Name = "Disco"
Disco.Parent = Frame
Disco.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Disco.BorderColor3 = Color3.fromRGB(0, 0, 0)
Disco.BorderSizePixel = 0
Disco.Position = UDim2.new(0.0214592274, 0, 0.59649539, 0)
Disco.Size = UDim2.new(0, 135, 0, 50)
Disco.Font = Enum.Font.Arcade
Disco.Text = "Disco"
Disco.TextColor3 = Color3.fromRGB(255, 255, 255)
Disco.TextSize = 14.000

Theme2.Name = "Theme2"
Theme2.Parent = Frame
Theme2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Theme2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Theme2.BorderSizePixel = 0
Theme2.Position = UDim2.new(0.35407725, 0, 0.592542708, 0)
Theme2.Size = UDim2.new(0, 135, 0, 50)
Theme2.Font = Enum.Font.Arcade
Theme2.Text = "Theme 2"
Theme2.TextColor3 = Color3.fromRGB(255, 255, 255)
Theme2.TextSize = 14.000

SteveSpam.Name = "SteveSpam"
SteveSpam.Parent = Frame
SteveSpam.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SteveSpam.BorderColor3 = Color3.fromRGB(0, 0, 0)
SteveSpam.BorderSizePixel = 0
SteveSpam.Position = UDim2.new(0.693133056, 0, 0.592542708, 0)
SteveSpam.Size = UDim2.new(0, 135, 0, 50)
SteveSpam.Font = Enum.Font.Arcade
SteveSpam.Text = "Steve Spam"
SteveSpam.TextColor3 = Color3.fromRGB(255, 255, 255)
SteveSpam.TextSize = 14.000

Frame1.Name = "Frame1"
Frame1.Parent = Frame
Frame1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame1.BorderSizePixel = 0
Frame1.Position = UDim2.new(-0.0240901578, 0, 0.997845113, 0)
Frame1.Size = UDim2.new(0, 487, 0, 44)

Frame2.Name = "Frame2"
Frame2.Parent = Frame
Frame2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame2.BorderSizePixel = 0
Frame2.Position = UDim2.new(-0.0240901578, 0, -0.286961555, 0)
Frame2.Size = UDim2.new(0, 487, 0, 44)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 2
TextLabel.Position = UDim2.new(-3.27441825e-08, 0, -0.613852799, 0)
TextLabel.Size = UDim2.new(0, 466, 0, 50)
TextLabel.Font = Enum.Font.Arcade
TextLabel.Text = "IdkWhatToPutHere gui v1.1"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 30.000

TextLabel_2.Name = "TextLabel_2"
TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 2
TextLabel_2.Position = UDim2.new(-0.0257510729, 0, 0.996536851, 0)
TextLabel_2.Size = UDim2.new(0, 487, 0, 44)
TextLabel_2.Font = Enum.Font.Arcade
TextLabel_2.Text = "By ThisPersonIsNoob"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 30.000

TextLabel_2_2.Name = "TextLabel_2"
TextLabel_2_2.Parent = Frame
TextLabel_2_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2_2.BorderSizePixel = 2
TextLabel_2_2.Position = UDim2.new(-0.0257511064, 0, -0.289177448, 0)
TextLabel_2_2.Size = UDim2.new(0, 487, 0, 44)
TextLabel_2_2.Font = Enum.Font.Arcade
TextLabel_2_2.Text = "Drag The White Box"
TextLabel_2_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2_2.TextScaled = true
TextLabel_2_2.TextSize = 30.000
TextLabel_2_2.TextWrapped = true

-- Scripts:

local function FIZJVPI_fake_script() -- Skybox.1 
	local script = Instance.new('LocalScript', Skybox)

	function click()
		s = Instance.new("Sky")
		s.Name = "Sky"
		s.Parent = game.Lighting
		s.SkyboxBk = "http://www.roblox.com/asset/?id=81568252624493"
		s.SkyboxDn = "http://www.roblox.com/asset/?id=81568252624493"
		s.SkyboxFt = "http://www.roblox.com/asset/?id=81568252624493"
		s.SkyboxLf = "http://www.roblox.com/asset/?id=81568252624493"
		s.SkyboxRt = "http://www.roblox.com/asset/?id=81568252624493"
		s.SkyboxUp = "http://www.roblox.com/asset/?id=81568252624493"
		game.Lighting.TimeOfDay = 12
	end
	
	script.Parent.MouseButton1Down:connect(click)
	
end
coroutine.wrap(FIZJVPI_fake_script)()
local function GVFD_fake_script() -- Decal.2 
	local script = Instance.new('LocalScript', Decal)

	function click()
		function exPro(root)
			for _, v in pairs(root:GetChildren()) do
				if v:IsA("Decal") and v.Texture ~= "http://www.roblox.com/asset/?id=81568252624493" then
					v.Parent = nil
				elseif v:IsA("BasePart") then
					v.Material = "Plastic"
					v.Transparency = 0
					local One = Instance.new("Decal", v)
					local Two = Instance.new("Decal", v)
					local Three = Instance.new("Decal", v)
					local Four = Instance.new("Decal", v)
					local Five = Instance.new("Decal", v)
					local Six = Instance.new("Decal", v)
					One.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					Two.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					Three.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					Four.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					Five.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					Six.Texture = "http://www.roblox.com/asset/?id=81568252624493"
					One.Face = "Front"
					Two.Face = "Back"
					Three.Face = "Right"
					Four.Face = "Left"
					Five.Face = "Top"
					Six.Face = "Bottom"
				end
				exPro(v)
			end
		end
		function asdf(root)
			for _, v in pairs(root:GetChildren()) do
				asdf(v)
			end
		end
		exPro(game.Workspace)
		asdf(game.Workspace)
	end
	
	script.Parent.MouseButton1Down:connect(click)
	
end
coroutine.wrap(GVFD_fake_script)()
local function BCTMISF_fake_script() -- Theme.Theme 
	local script = Instance.new('LocalScript', Theme)

	local sound = script.Parent.Sound
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		sound:Play()
	end)
end
coroutine.wrap(BCTMISF_fake_script)()
local function EOULBJL_fake_script() -- Disco.Disco 
	local script = Instance.new('LocalScript', Disco)

	script.Parent.MouseButton1Click:Connect(function()
		local Lighting = game:GetService("Lighting")
		local ColorCorrection = Instance.new("ColorCorrectionEffect", Lighting)
	
		function zigzag(X) 
			return math.acos(math.cos(X*math.pi))/math.pi
		end
	
		Counter = 0
	
		Lighting.TimeOfDay = "15:00"
	
		while wait(0.1) do 
			ColorCorrection.TintColor = Color3.fromHSV(zigzag(Counter),1,1)
			Lighting.Ambient = Color3.fromHSV(zigzag(Counter),1,1)
			Counter += 0.01
		end
	end)
end
coroutine.wrap(EOULBJL_fake_script)()
local function IBUJGQ_fake_script() -- Theme2.Theme2 
	local script = Instance.new('LocalScript', Theme2)

	local sound = script.Parent.Sound2
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		sound:Play()
	end)
end
coroutine.wrap(IBUJGQ_fake_script)()
local function DULJ_fake_script() -- SteveSpam.SteveSpam 
	local script = Instance.new('LocalScript', SteveSpam)

	function click()
		function exPro(root)
			for _, v in pairs(root:GetChildren()) do
				if v:IsA("Decal") and v.Texture ~= "http://www.roblox.com/asset/?id=103088480247113" then
					v.Parent = nil
				elseif v:IsA("BasePart") then
					v.Material = "Plastic"
					v.Transparency = 0
					local One = Instance.new("Decal", v)
					local Two = Instance.new("Decal", v)
					local Three = Instance.new("Decal", v)
					local Four = Instance.new("Decal", v)
					local Five = Instance.new("Decal", v)
					local Six = Instance.new("Decal", v)
					One.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					Two.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					Three.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					Four.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					Five.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					Six.Texture = "http://www.roblox.com/asset/?id=103088480247113"
					One.Face = "Front"
					Two.Face = "Back"
					Three.Face = "Right"
					Four.Face = "Left"
					Five.Face = "Top"
					Six.Face = "Bottom"
				end
				exPro(v)
			end
		end
		function asdf(root)
			for _, v in pairs(root:GetChildren()) do
				asdf(v)
			end
		end
		exPro(game.Workspace)
		asdf(game.Workspace)
	end
	
	script.Parent.MouseButton1Down:connect(click)
	
	
	function click()
		s = Instance.new("Sky")
		s.Name = "Sky"
		s.Parent = game.Lighting
		s.SkyboxBk = "http://www.roblox.com/asset/?id=103088480247113"
		s.SkyboxDn = "http://www.roblox.com/asset/?id=103088480247113"
		s.SkyboxFt = "http://www.roblox.com/asset/?id=103088480247113"
		s.SkyboxLf = "http://www.roblox.com/asset/?id=103088480247113"
		s.SkyboxRt = "http://www.roblox.com/asset/?id=103088480247113"
		s.SkyboxUp = "http://www.roblox.com/asset/?id=103088480247113"
		game.Lighting.TimeOfDay = 12
	end
	
	script.Parent.MouseButton1Down:connect(click)
	
end
coroutine.wrap(DULJ_fake_script)()
local function COSSSI_fake_script() -- Frame.DraggableGUi 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.1
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(COSSSI_fake_script)()
