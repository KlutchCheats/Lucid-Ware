-- Gui to Lua
-- Version: 3.2

-- Instances:

local LucidWare = Instance.new("ScreenGui")
local Boarder = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Main = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local MainCheats = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Container = Instance.new("ScrollingFrame")
local ScriptHubName = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Name = Instance.new("TextLabel")
local UIGridLayout = Instance.new("UIGridLayout")
local Chams = Instance.new("Frame")
local UICorner_5 = Instance.new("UICorner")
local Name_2 = Instance.new("TextLabel")
local Toggle = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Aimbot = Instance.new("Frame")
local UICorner_7 = Instance.new("UICorner")
local Name_3 = Instance.new("TextLabel")
local Toggle_2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local FovCircle = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local Name_4 = Instance.new("TextLabel")
local Toggle_3 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local VisibleCheck = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local Name_5 = Instance.new("TextLabel")
local Toggle_4 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TeamCheck = Instance.new("Frame")
local UICorner_13 = Instance.new("UICorner")
local Name_6 = Instance.new("TextLabel")
local Toggle_5 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local Main_2 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")

--Properties:

LucidWare.Name = "Lucid-Ware"
LucidWare.Parent = game:GetService("CoreGui")
LucidWare.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Boarder.Name = "Boarder"
Boarder.Parent = LucidWare
Boarder.BackgroundColor3 = Color3.fromRGB(0, 179, 255)
Boarder.Position = UDim2.new(0.370397121, 0, 0.317596555, 0)
Boarder.Size = UDim2.new(0, 359, 0, 255)
Boarder.Active = true
Boarder.Draggable = true

UICorner.Parent = Boarder

Main.Name = "Main"
Main.Parent = Boarder
Main.BackgroundColor3 = Color3.fromRGB(18, 18, 18)
Main.Position = UDim2.new(0.00200000009, 0, 0.00499999989, 0)
Main.Size = UDim2.new(0, 357, 0, 253)
Main.ZIndex = 2

UICorner_2.Parent = Main

MainCheats.Name = "MainCheats"
MainCheats.Parent = Main
MainCheats.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
MainCheats.Position = UDim2.new(0.0168067235, 0, 0.0988142267, 0)
MainCheats.Size = UDim2.new(0, 345, 0, 222)
MainCheats.ZIndex = 3

UICorner_3.Parent = MainCheats

Container.Name = "Container"
Container.Parent = MainCheats
Container.Active = true
Container.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Container.BackgroundTransparency = 1.000
Container.BorderSizePixel = 0
Container.Position = UDim2.new(0.0173913036, 0, 0.0360360369, 0)
Container.Size = UDim2.new(0, 333, 0, 214)
Container.ZIndex = 8
Container.CanvasSize = UDim2.new(0, 0, 1.35000002, 0)

ScriptHubName.Name = "ScriptHubName"
ScriptHubName.Parent = Container
ScriptHubName.BackgroundColor3 = Color3.fromRGB(0, 179, 255)
ScriptHubName.Position = UDim2.new(0.00736142648, 0, -0.000658552221, 0)
ScriptHubName.Size = UDim2.new(0, 306, 0, 30)
ScriptHubName.ZIndex = 9

UICorner_4.Parent = ScriptHubName

Name.Name = "Name"
Name.Parent = ScriptHubName
Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name.BackgroundTransparency = 1.000
Name.Size = UDim2.new(0, 315, 0, 40)
Name.ZIndex = 9
Name.Font = Enum.Font.FredokaOne
Name.Text = "Lucid-Ware"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true

UIGridLayout.Parent = Container
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 5, 0, 8)
UIGridLayout.CellSize = UDim2.new(0, 315, 0, 40)

Chams.Name = "Chams"
Chams.Parent = Container
Chams.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Chams.Size = UDim2.new(0, 100, 0, 100)

UICorner_5.Parent = Chams

Name_2.Name = "Name"
Name_2.Parent = Chams
Name_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_2.BackgroundTransparency = 1.000
Name_2.Position = UDim2.new(0.0190476198, 0, 0.075000003, 0)
Name_2.Size = UDim2.new(0, 194, 0, 34)
Name_2.ZIndex = 9
Name_2.Font = Enum.Font.FredokaOne
Name_2.Text = "Chams"
Name_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_2.TextScaled = true
Name_2.TextSize = 14.000
Name_2.TextWrapped = true
Name_2.TextXAlignment = Enum.TextXAlignment.Left

Toggle.Name = "Toggle"
Toggle.Parent = Chams
Toggle.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toggle.Position = UDim2.new(0.892063498, 0, 0.150000006, 0)
Toggle.Size = UDim2.new(0, 28, 0, 28)
Toggle.ZIndex = 9
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = ""
Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle.TextSize = 14.000

UICorner_6.Parent = Toggle

Aimbot.Name = "Aimbot"
Aimbot.Parent = Container
Aimbot.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Aimbot.Size = UDim2.new(0, 100, 0, 100)

UICorner_7.Parent = Aimbot

Name_3.Name = "Name"
Name_3.Parent = Aimbot
Name_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_3.BackgroundTransparency = 1.000
Name_3.Position = UDim2.new(0.0190476198, 0, 0.075000003, 0)
Name_3.Size = UDim2.new(0, 194, 0, 34)
Name_3.ZIndex = 9
Name_3.Font = Enum.Font.FredokaOne
Name_3.Text = "Aimbot"
Name_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_3.TextScaled = true
Name_3.TextSize = 14.000
Name_3.TextWrapped = true
Name_3.TextXAlignment = Enum.TextXAlignment.Left

Toggle_2.Name = "Toggle"
Toggle_2.Parent = Aimbot
Toggle_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toggle_2.Position = UDim2.new(0.892063498, 0, 0.150000006, 0)
Toggle_2.Size = UDim2.new(0, 28, 0, 28)
Toggle_2.ZIndex = 9
Toggle_2.Font = Enum.Font.SourceSans
Toggle_2.Text = ""
Toggle_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle_2.TextSize = 14.000

UICorner_8.Parent = Toggle_2

FovCircle.Name = "FovCircle"
FovCircle.Parent = Container
FovCircle.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
FovCircle.Size = UDim2.new(0, 100, 0, 100)

UICorner_9.Parent = FovCircle

Name_4.Name = "Name"
Name_4.Parent = FovCircle
Name_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_4.BackgroundTransparency = 1.000
Name_4.Position = UDim2.new(0.0190476198, 0, 0.075000003, 0)
Name_4.Size = UDim2.new(0, 194, 0, 34)
Name_4.ZIndex = 9
Name_4.Font = Enum.Font.FredokaOne
Name_4.Text = "FOV Circle"
Name_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_4.TextScaled = true
Name_4.TextSize = 14.000
Name_4.TextWrapped = true
Name_4.TextXAlignment = Enum.TextXAlignment.Left

Toggle_3.Name = "Toggle"
Toggle_3.Parent = FovCircle
Toggle_3.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toggle_3.Position = UDim2.new(0.892063498, 0, 0.150000006, 0)
Toggle_3.Size = UDim2.new(0, 28, 0, 28)
Toggle_3.ZIndex = 9
Toggle_3.Font = Enum.Font.SourceSans
Toggle_3.Text = ""
Toggle_3.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle_3.TextSize = 14.000

UICorner_10.Parent = Toggle_3

VisibleCheck.Name = "VisibleCheck"
VisibleCheck.Parent = Container
VisibleCheck.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
VisibleCheck.Size = UDim2.new(0, 100, 0, 100)

UICorner_11.Parent = VisibleCheck

Name_5.Name = "Name"
Name_5.Parent = VisibleCheck
Name_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_5.BackgroundTransparency = 1.000
Name_5.Position = UDim2.new(0.0190476198, 0, 0.075000003, 0)
Name_5.Size = UDim2.new(0, 194, 0, 34)
Name_5.ZIndex = 9
Name_5.Font = Enum.Font.FredokaOne
Name_5.Text = "Visible Check"
Name_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_5.TextScaled = true
Name_5.TextSize = 14.000
Name_5.TextWrapped = true
Name_5.TextXAlignment = Enum.TextXAlignment.Left

Toggle_4.Name = "Toggle"
Toggle_4.Parent = VisibleCheck
Toggle_4.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toggle_4.Position = UDim2.new(0.892063498, 0, 0.150000006, 0)
Toggle_4.Size = UDim2.new(0, 28, 0, 28)
Toggle_4.ZIndex = 9
Toggle_4.Font = Enum.Font.SourceSans
Toggle_4.Text = ""
Toggle_4.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle_4.TextSize = 14.000

UICorner_12.Parent = Toggle_4

TeamCheck.Name = "TeamCheck"
TeamCheck.Parent = Container
TeamCheck.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TeamCheck.Size = UDim2.new(0, 100, 0, 100)

UICorner_13.Parent = TeamCheck

Name_6.Name = "Name"
Name_6.Parent = TeamCheck
Name_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_6.BackgroundTransparency = 1.000
Name_6.Position = UDim2.new(0.0190476198, 0, 0.075000003, 0)
Name_6.Size = UDim2.new(0, 194, 0, 34)
Name_6.ZIndex = 9
Name_6.Font = Enum.Font.FredokaOne
Name_6.Text = "Team Check"
Name_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_6.TextScaled = true
Name_6.TextSize = 14.000
Name_6.TextWrapped = true
Name_6.TextXAlignment = Enum.TextXAlignment.Left

Toggle_5.Name = "Toggle"
Toggle_5.Parent = TeamCheck
Toggle_5.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toggle_5.Position = UDim2.new(0.892063498, 0, 0.150000006, 0)
Toggle_5.Size = UDim2.new(0, 28, 0, 28)
Toggle_5.ZIndex = 9
Toggle_5.Font = Enum.Font.SourceSans
Toggle_5.Text = ""
Toggle_5.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle_5.TextSize = 14.000

UICorner_14.Parent = Toggle_5

Main_2.Name = "Main"
Main_2.Parent = Main
Main_2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Main_2.BorderSizePixel = 0
Main_2.Position = UDim2.new(0.0168067235, 0, 0.0237154141, 0)
Main_2.Size = UDim2.new(0, 75, 0, 27)
Main_2.ZIndex = 4
Main_2.Font = Enum.Font.FredokaOne
Main_2.Text = "MAIN"
Main_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Main_2.TextSize = 14.000

UICorner_15.Parent = Main_2

-- Scripts:

local function MTVSM_fake_script() -- Toggle.ToggleScript 
	local script = Instance.new('LocalScript', Toggle)

	local enabled = false
	local visiblecheck = false
	local teamcheck = false
	local container = script.Parent.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		enabled = not enabled
		
		if enabled then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0,255,0)
			
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,0)
		end
	end)
	
	container.TeamCheck.Toggle.MouseButton1Click:Connect(function()
		teamcheck = not teamcheck
		
		for i,v in pairs(game:GetService("Players"):GetPlayers()) do
            if v.Character then
				for i,v in pairs(v.Character:GetChildren()) do
					if v.Name == "cham" then
						v:Destroy()
					end
				end
			end
        end
	end)
	
	container.VisibleCheck.Toggle.MouseButton1Click:Connect(function()
		visiblecheck = not visiblecheck
	
		for i,v in pairs(game:GetService("Players"):GetPlayers()) do
            if v.Character then
                for i,v in pairs(v.Character:GetChildren()) do
                    if v.Name == "cham" then
                        v:Destroy()
                    end
                end
            end
        end
	end)
	
	game:GetService("RunService").RenderStepped:Connect(function()
		local plr = game.Players.LocalPlayer
		local char = plr.Character or plr.CharacterAdded:Wait()
		
		if enabled == false then
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
                if v.Character then
                    for i,v in pairs(v.Character:GetChildren()) do
                        if v.Name == "cham" then
                            v:Destroy()
                        end
                    end
                end
			end
		end

        if teamcheck == true then
            for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				if v.Character then
                    for i,v in pairs(plr.Character:GetChildren()) do
						if v.Name == "cham" then
							v:Destroy()
						end
					end
                end
			end
        end
	
		for i,v in pairs(game:GetService("Players"):GetPlayers()) do
			if teamcheck and enabled then
				if v.Team ~= plr.Team then
					if v.Character then
						if not v.Character:FindFirstChild("cham") and enabled == true then
							local cham = Instance.new("Highlight")
							cham.Name = "cham"
							cham.FillTransparency = 0.4
							cham.Parent = v.Character
							
							if visiblecheck == false then
								cham.FillColor = Color3.fromRGB(255,0,0)
							end
						end
	
						if v.Character and enabled == true and visiblecheck then
							local cham = v.Character.cham
							local params = RaycastParams.new()
							params.IgnoreWater = true
							params.FilterType= Enum.RaycastFilterType.Blacklist
							params.FilterDescendantsInstances = {char}
							local result = workspace:Raycast(workspace.CurrentCamera.CFrame.Position,(v.Character:WaitForChild("HumanoidRootPart").Position-workspace.CurrentCamera.CFrame.Position).Unit*9e9,params)
							if result then
								if result.Instance:IsDescendantOf(v.Character) then
									cham.FillColor = Color3.fromRGB(0,255,0)
								else
									cham.FillColor = Color3.fromRGB(255,0,0)
								end
							end
						end
					end
				end 
				
			else
				if v.Character and enabled then
					if not v.Character:FindFirstChild("cham") and enabled == true then
						local cham = Instance.new("Highlight")
						cham.Name = "cham"
						cham.FillTransparency = 0.4
						cham.Parent = v.Character
						
						if visiblecheck == false then
							cham.FillColor = Color3.fromRGB(255,0,0)
						end
					end
	
					if v.Character and enabled == true and visiblecheck then
						local cham = v.Character.cham
						local params = RaycastParams.new()
						params.IgnoreWater = true
						params.FilterType= Enum.RaycastFilterType.Blacklist
						params.FilterDescendantsInstances = {char}
						local result = workspace:Raycast(char.Head.Position,(v.Character.HumanoidRootPart.Position-char.Head.Position).Unit*9e9,params)
						if result then
							if result.Instance:IsDescendantOf(v.Character) then
								cham.FillColor = Color3.fromRGB(0,255,0)
							else
								cham.FillColor = Color3.fromRGB(255,0,0)
							end
						end
					end
				end
			end
		end
	end)
end
coroutine.wrap(MTVSM_fake_script)()
local function NDQSKU_fake_script() -- Toggle_2.ToggleScript 
	local script = Instance.new('LocalScript', Toggle_2)

	local enabled = false
	
	getgenv().Aimbot = true
	
	local ws = game:GetService("Workspace")
	local cam = ws.CurrentCamera
	local plrs = game:GetService("Players")
	local plr = plrs.LocalPlayer
	local ms = plr:GetMouse()
	local RunService = game:GetService("RunService")
	local uis = game:GetService("UserInputService")
	local fovenabled = false
	local teamcheck = false
	
	local aiming = false
	
	local fov = Drawing.new("Circle")
	fov.Thickness = 1
	fov.Radius = 50
	fov.Position = Vector2.new(cam.ViewportSize.X/2, cam.ViewportSize.Y/2)
	
	local AimbotSettings = {
		aimbotEnabled = true,
		teamcheck = true,
		useFov = false,
		fovSize = 50,
		AimPart = "Head",
		keybind = Enum.UserInputType.MouseButton2
	}
	
	script.Parent.MouseButton1Click:Connect(function()
		enabled = not enabled
	
		if enabled then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0,255,0)
	
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,0)
		end
	end)
	
	script.Parent.Parent.Parent.FovCircle.Toggle.MouseButton1Click:Connect(function()
		fovenabled = not fovenabled
	end)
	
	script.Parent.Parent.Parent.TeamCheck.Toggle.MouseButton1Click:Connect(function()
		teamcheck = not teamcheck
	end)
	
	function gcp()
		local dist = math.huge
		local closest = nil
	
		for i,v in pairs(plrs:GetPlayers()) do
			if v ~= plr and getgenv().Aimbot and v.Character and v.Character.Humanoid.Health > 0 then
				if teamcheck then
					if v.TeamColor ~= plr.TeamColor then
						local pos = cam:WorldToScreenPoint(v.Character.HumanoidRootPart.Position)
						local mag = (Vector2.new(ms.X, ms.Y) - Vector2.new(pos.X, pos.Y)).magnitude
	
						if mag < dist then
							if fovenabled then
								if mag < AimbotSettings.fovSize then
									dist = mag
									closest = v
								end
							end
						end
					end
					
				else
					local pos = cam:WorldToScreenPoint(v.Character.HumanoidRootPart.Position)
					local mag = (Vector2.new(ms.X, ms.Y) - Vector2.new(pos.X, pos.Y)).magnitude
	
					if mag < dist then
						if fovenabled then
							if mag < AimbotSettings.fovSize then
								dist = mag
								closest = v
							end

                        else
                            dist = mag
							closest = v
						end
					end
				end
			end
		end
	
		return closest
	end
	
	uis.InputBegan:Connect(function(a)
		if a.UserInputType == AimbotSettings.keybind then
			aiming = true
		end
	end)
	
	uis.InputEnded:Connect(function(a)
		if a.UserInputType == AimbotSettings.keybind then
			aiming = false
		end
	end)
	
	RunService.RenderStepped:Connect(function()
        fov.Visible = fovenabled
		if aiming and getgenv().Aimbot and AimbotSettings.aimbotEnabled and enabled then
			local theclosest = gcp().Character or gcp().CharacterAdded:Wait()
			cam.CFrame = CFrame.new(cam.CFrame.Position, theclosest.Head.Position)
		end
	end)
end
coroutine.wrap(NDQSKU_fake_script)()
local function KOYVX_fake_script() -- Toggle_3.ToggleScript 
	local script = Instance.new('LocalScript', Toggle_3)

	local enabled = false
	
	script.Parent.MouseButton1Click:Connect(function()
		enabled = not enabled
		
		if enabled then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0,255,0)
			
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,0)
		end
	end)
end
coroutine.wrap(KOYVX_fake_script)()
local function HBVFICZ_fake_script() -- Toggle_4.ToggleScript 
	local script = Instance.new('LocalScript', Toggle_4)

	local enabled = false
	
	script.Parent.MouseButton1Click:Connect(function()
		enabled = not enabled
		
		if enabled then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0,255,0)
			
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,0)
		end
	end)
end
coroutine.wrap(HBVFICZ_fake_script)()
local function INNGZN_fake_script() -- Toggle_5.ToggleScript 
	local script = Instance.new('LocalScript', Toggle_5)

	local enabled = false
	
	script.Parent.MouseButton1Click:Connect(function()
		enabled = not enabled
		
		if enabled then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0,255,0)
			
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,0)
		end
	end)
end
coroutine.wrap(INNGZN_fake_script)()
local function OTGT_fake_script() -- LucidWare.ToggleUi 
	local script = Instance.new('LocalScript', LucidWare)

	local uis = game:GetService("UserInputService")
	
	uis.InputBegan:Connect(function(a)
		if a.KeyCode == Enum.KeyCode.RightControl then
			script.Parent.Enabled = not script.Parent.Enabled
		end
	end)
end
coroutine.wrap(OTGT_fake_script)()
