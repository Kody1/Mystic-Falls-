
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local password = Instance.new("TextBox")
local user = Instance.new("TextBox")
local login = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
main.Position = UDim2.new(0.435946465, 0, 0.176842108, 0)
main.Size = UDim2.new(0, 247, 0, 304)
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(0, 247, 0, 46)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Login Screen"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

password.Name = "password"
password.Parent = main
password.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
password.Position = UDim2.new(0.0931174085, 0, 0.524758875, 0)
password.Size = UDim2.new(0, 200, 0, 50)
password.Font = Enum.Font.SourceSans
password.Text = "Password"
password.TextColor3 = Color3.fromRGB(255, 255, 255)
password.TextScaled = true
password.TextSize = 14.000
password.TextWrapped = true

user.Name = "user"
user.Parent = main
user.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
user.Position = UDim2.new(0.0931174085, 0, 0.293893129, 0)
user.Size = UDim2.new(0, 200, 0, 50)
user.Font = Enum.Font.SourceSans
user.Text = "Username"
user.TextColor3 = Color3.fromRGB(255, 255, 255)
user.TextScaled = true
user.TextSize = 14.000
user.TextWrapped = true

login.Name = "login"
login.Parent = main
login.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
login.Position = UDim2.new(0.206477731, 0, 0.792712986, 0)
login.Size = UDim2.new(0, 143, 0, 50)
login.Font = Enum.Font.SourceSans
login.Text = "Login"
login.TextColor3 = Color3.fromRGB(255, 255, 255)
login.TextScaled = true
login.TextSize = 14.000
login.TextWrapped = true
login.MouseButton1Down:connect(function()
	if user.Text == "xhIJ" and password.Text == "0905978" then
		login.Visible = false
		main.Visible = false
		


		local ScreenGui = Instance.new("ScreenGui")
		local main = Instance.new("Frame")
		local TextLabel = Instance.new("TextLabel")
		local seeghost = Instance.new("TextButton")
		local channel = Instance.new("TextButton")
		local TextLabel_2 = Instance.new("TextLabel")
		local feed = Instance.new("TextButton")
		local snap = Instance.new("TextButton")
		local motus = Instance.new("TextButton")
		local invis = Instance.new("TextButton")
		local bomb = Instance.new("TextButton")
		local selfres = Instance.new("TextButton")
		local pain = Instance.new("TextButton")
		local reset = Instance.new("TextButton")
		local teleport = Instance.new("TextButton")
		local bite = Instance.new("TextButton")
		local TextLabel_3 = Instance.new("TextLabel")
		local vervain = Instance.new("TextButton")
		local TextLabel_4 = Instance.new("TextLabel")
		local TextLabel_5 = Instance.new("TextLabel")

		--Properties:

		ScreenGui.Parent = game.CoreGui
		ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

		main.Name = "main"
		main.Parent = ScreenGui
		main.Active = true
		main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		main.Position = UDim2.new(-0.000955998898, 0, 0, 0)
		main.Size = UDim2.new(0, 195, 0, 475)
		main.Active = true
		main.Draggable = true

		TextLabel.Parent = main
		TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel.BackgroundTransparency = 1.000
		TextLabel.Position = UDim2.new(0.037714228, 0, 0, 0)
		TextLabel.Size = UDim2.new(0, 195, 0, 50)
		TextLabel.Font = Enum.Font.PatrickHand
		TextLabel.Text = "Mystic Falls"
		TextLabel.TextColor3 = Color3.fromRGB(255, 0, 127)
		TextLabel.TextScaled = true
		TextLabel.TextSize = 14.000
		TextLabel.TextWrapped = true

		seeghost.Name = "seeghost"
		seeghost.Parent = main
		seeghost.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		seeghost.Position = UDim2.new(0.313238144, 0, 0.911579013, 0)
		seeghost.Size = UDim2.new(0, 79, 0, 41)
		seeghost.Font = Enum.Font.ArialBold
		seeghost.Text = "See Ghost"
		seeghost.TextColor3 = Color3.fromRGB(85, 170, 255)
		seeghost.TextSize = 14.000
		seeghost.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character or plr.CharacterAdded:Wait()
			local fold = Instance.new("Folder")
			fold.Name = "SeeGhosts"
			fold.Parent = char
		end)

		channel.Name = "channel"
		channel.Parent = main
		channel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		channel.Position = UDim2.new(0.00185305276, 0, 0.258947372, 0)
		channel.Size = UDim2.new(0, 96, 0, 50)
		channel.Font = Enum.Font.ArialBold
		channel.Text = "Infinite Channeling"
		channel.TextColor3 = Color3.fromRGB(255, 85, 255)
		channel.TextSize = 14.000
		channel.TextWrapped = true
		channel.MouseButton1Down:connect(function()
			repeat
				wait(7)
				local Player = game.Players.LocalPlayer
				local Character = Player.Character or Player.CharacterAdded:Wait()
				local A_1 = "Magic"
				local A_2 = 
					{
						[1] = "requestChanneling", 
						[2] = Character
					}
				local Event = game:GetService("ReplicatedStorage").Events.Witch
				Event:FireServer(A_1, A_2)

				wait(1)

				local Player = game.Players.LocalPlayer
				local A_1 = "Channel"
				local A_2 = 
					{
						[1] = true, 
						[2] = Character
					}
				local Event = game:GetService("ReplicatedStorage").Events.Witch
				Event:FireServer(A_1, A_2)

				wait(3)

				local Channel = Character:WaitForChild("Channeling")
				Channel:Destroy()

				local Channel = Character:WaitForChild("Channeling")
				Channel:Destroy()

			until Character.Magic.Value == 131072000
		end)

		TextLabel_2.Parent = main
		TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel_2.BackgroundTransparency = 1.000
		TextLabel_2.Position = UDim2.new(0.153686732, 0, 0.0715789199, 0)
		TextLabel_2.Size = UDim2.new(0, 151, 0, 50)
		TextLabel_2.Font = Enum.Font.PatrickHand
		TextLabel_2.Text = "Credits:Jaylen "
		TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 127)
		TextLabel_2.TextScaled = true
		TextLabel_2.TextSize = 14.000
		TextLabel_2.TextWrapped = true

		feed.Name = "feed"
		feed.Parent = main
		feed.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		feed.Position = UDim2.new(0, 0, 0.772631526, 0)
		feed.Size = UDim2.new(0, 96, 0, 50)
		feed.Font = Enum.Font.ArialBold
		feed.Text = "SuperFeed (Y) Must be a vamp"
		feed.TextColor3 = Color3.fromRGB(170, 0, 0)
		feed.TextSize = 14.000
		feed.TextWrapped = true
		feed.MouseButton1Down:connect(function()
			local LocalPlayer = game.Players.LocalPlayer
			local Character = LocalPlayer.Character
			local Humanoid = Character.Humanoid
			local Mouse = LocalPlayer:GetMouse()
			local Vampire = game:GetService("ReplicatedStorage").Events.Vampire

			game:GetService("UserInputService").InputBegan:Connect(function(Input, isTyping)
				if isTyping then return end
				if Input.KeyCode == Enum.KeyCode.Y and Mouse.Target then
					local Target = Mouse.Target.Parent:FindFirstChild("Humanoid") or Mouse.Target.Parent.Parent:FindFirstChild("Humanoid")
					if Target then
						local Player = game:GetService("Players"):GetPlayerFromCharacter(Target.Parent)
						Vampire:FireServer("Feed", {Player.Character})
					end
				end
			end)
		end)

		snap.Name = "snap"
		snap.Parent = main
		snap.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		snap.Position = UDim2.new(0.00185305346, 0, 0.576842129, 0)
		snap.Size = UDim2.new(0, 96, 0, 48)
		snap.Font = Enum.Font.ArialBold
		snap.Text = "Snap Everyone Near u (Q) Must Be A Witch"
		snap.TextColor3 = Color3.fromRGB(255, 85, 255)
		snap.TextSize = 14.000
		snap.TextWrapped = true
		snap.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'Q'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "SnapAll", 
							[2] = mouse.Hit.p
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)


		motus.Name = "motus"
		motus.Parent = main
		motus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		motus.Position = UDim2.new(0.499262363, 0, 0.46947372, 0)
		motus.Size = UDim2.new(0, 96, 0, 50)
		motus.Font = Enum.Font.ArialBold
		motus.Text = "Motus (M) Must Be A Witch"
		motus.TextColor3 = Color3.fromRGB(255, 85, 255)
		motus.TextSize = 14.000
		motus.TextWrapped = true
		motus.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'M'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "Motus"
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)

		invis.Name = "invis"
		invis.Parent = main
		invis.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		invis.Position = UDim2.new(0.00185304531, 0, 0.364210516, 0)
		invis.Size = UDim2.new(0, 95, 0, 50)
		invis.Font = Enum.Font.ArialBold
		invis.Text = "Invisique (F) Must Be A Witch"
		invis.TextColor3 = Color3.fromRGB(255, 85, 255)
		invis.TextSize = 14.000
		invis.TextWrapped = true
		invis.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'F'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "Invisibility"
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)


		bomb.Name = "bomb"
		bomb.Parent = main
		bomb.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		bomb.Position = UDim2.new(0.499262363, 0, 0.364210516, 0)
		bomb.Size = UDim2.new(0, 96, 0, 50)
		bomb.Font = Enum.Font.ArialBold
		bomb.Text = "Bruciare/Bomb Spell (B) Must Be A Witch"
		bomb.TextColor3 = Color3.fromRGB(255, 85, 255)
		bomb.TextSize = 14.000
		bomb.TextWrapped = true
		bomb.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'B'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "Explosion", 
							[2] = mouse.Hit.p
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)


		selfres.Name = "selfres"
		selfres.Parent = main
		selfres.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		selfres.Position = UDim2.new(-0.00279767951, 0, 0.911579013, 0)
		selfres.Size = UDim2.new(0, 60, 0, 41)
		selfres.Font = Enum.Font.ArialBold
		selfres.Text = "Self Res Gui"
		selfres.TextColor3 = Color3.fromRGB(85, 170, 255)
		selfres.TextSize = 14.000
		selfres.TextWrapped = true
		selfres.MouseButton1Down:connect(function()
			--Made By The Anonymous Elf
			local MysticFalls = Instance.new("ScreenGui")
			local main = Instance.new("Frame")
			local Title = Instance.new("TextLabel")
			local ChannelRemover = Instance.new("TextButton")
			local LifeBringer = Instance.new("TextButton")
			local StakeFinder = Instance.new("TextButton")
			local Closer = Instance.new("TextButton")

			MysticFalls.Name = "MysticFalls"
			MysticFalls.Parent = game.CoreGui
			MysticFalls.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

			main.Name = "main"
			main.Parent = MysticFalls
			main.BackgroundColor3 = Color3.fromRGB(62, 0, 0)
			main.BorderSizePixel = 2
			main.Position = UDim2.new(0.0907158107, 0, 0.175182492, 0)
			main.Size = UDim2.new(0, 389, 0, 544)
			main.Active = true
			main.Draggable = true

			Title.Name = "Title"
			Title.Parent = main
			Title.BackgroundColor3 = Color3.fromRGB(62, 0, 0)
			Title.BackgroundTransparency = 1.000
			Title.Size = UDim2.new(0, 389, 0, 81)
			Title.Font = Enum.Font.Fondamento
			Title.Text = "Mystic Falls: GUI"
			Title.TextColor3 = Color3.fromRGB(0, 0, 0)
			Title.TextScaled = true
			Title.TextSize = 14.000
			Title.TextStrokeTransparency = 0.000
			Title.TextWrapped = true


			---------
			StakeFinder.MouseButton1Down:connect(function()
				local Player = game.Players.LocalPlayer
				local Character = Player.Character
				local WoodenStake = game.Workspace:WaitForChild("WoodenStake")
				local WhiteOakStake = game.Workspace:WaitForChild("WhiteOakStake")
				if WoodenStake then
					Character.UpperTorso.CFrame = WoodenStake.Handle.CFrame 
				end
				if WhiteOakStake then
					Character.UpperTorso.CFrame = WhiteOakStake.Handle.CFrame 
				end

			end)
			------------------------------------------------
			Closer.Name = "Close"
			Closer.Parent = main 
			Closer.BackgroundColor3 = Color3.fromRGB(20, 0, 0)
			Closer.BackgroundTransparency = 0.600
			Closer.BorderColor3 = Color3.fromRGB(0, 0, 0)
			Closer.BorderSizePixel = 4
			Closer.Position = UDim2.new(0.241645247, 0, 0.534926474, 0)
			Closer.Size = UDim2.new(0, 200, 0, 50)
			Closer.Font = Enum.Font.Fondamento
			Closer.Text = "Close"
			Closer.TextColor3 = Color3.fromRGB(0, 0, 0)
			Closer.TextScaled = true
			Closer.TextSize = 14.000
			Closer.TextStrokeTransparency = 0.000
			Closer.TextWrapped = true
			---------
			Closer.MouseButton1Down:connect(function()
				local Player = game.Players.LocalPlayer
				local Character = Player.Character
				Character.Humanoid.ragdoll.Value = false
				MysticFalls:Destroy()

			end)
			-----------------------------------------------------------
			ChannelRemover.Name = "Channel Remover"
			ChannelRemover.Parent = main
			ChannelRemover.BackgroundColor3 = Color3.fromRGB(20, 0, 0)
			ChannelRemover.BackgroundTransparency = 0.600
			ChannelRemover.BorderColor3 = Color3.fromRGB(0, 0, 0)
			ChannelRemover.BorderSizePixel = 4
			ChannelRemover.Position = UDim2.new(0.241645247, 0, 0.189338237, 0)
			ChannelRemover.Size = UDim2.new(0, 200, 0, 50)
			ChannelRemover.Font = Enum.Font.Fondamento
			ChannelRemover.Text = "Channel Remover"
			ChannelRemover.TextColor3 = Color3.fromRGB(0, 0, 0)
			ChannelRemover.TextScaled = true
			ChannelRemover.TextSize = 14.000
			ChannelRemover.TextStrokeTransparency = 0.000
			ChannelRemover.TextWrapped = true
			---------
			ChannelRemover.MouseButton1Down:connect(function()
				local Player = game.Players.LocalPlayer
				local Character = Player.Character
				Character.Channeling:Destroy()
			end)
			-----------------------------------------------------------
			LifeBringer.Name = "LifeBringer"
			LifeBringer.Parent = main
			LifeBringer.BackgroundColor3 = Color3.fromRGB(20, 0, 0)
			LifeBringer.BackgroundTransparency = 0.600
			LifeBringer.BorderColor3 = Color3.fromRGB(0, 0, 0)
			LifeBringer.BorderSizePixel = 4
			LifeBringer.Position = UDim2.new(0.241645247, 0, 0.365808845, 0)
			LifeBringer.Size = UDim2.new(0, 200, 0, 50)
			LifeBringer.Font = Enum.Font.Fondamento
			LifeBringer.Text = "Come Back To Life"
			LifeBringer.TextColor3 = Color3.fromRGB(0, 0, 0)
			LifeBringer.TextScaled = true
			LifeBringer.TextSize = 14.000
			LifeBringer.TextStrokeTransparency = 0.000
			LifeBringer.TextWrapped = true
			--------------------------
			LifeBringer.MouseButton1Down:connect(function()
				local Player = game.Players.LocalPlayer
				local Character = Player.Character
				Character.OtherSide:Destroy()
				if Character:FindFirstChild("WitchPowers") then
					local Witch = Character.Witch
					Witch.Disabled = false
					local Wp = Character.WitchPowers:GetDescendants()
					for counter,Wp in pairs(Wp) do
						if Wp.ClassName == "LocalScript" then
							Wp.Disabled = false
						end
					end
				end
				if Character:FindFirstChild("VampirePowers") then
					local Vp = Character.VampirePowers:GetDescendants()
					for counter,Vp in pairs(Vp) do
						if Vp.ClassName == "LocalScript" then
							Vp.Disabled = false
						end
					end
				end
			end)
			-----------------------------------------------------------
		end)

		pain.Name = "pain"
		pain.Parent = main
		pain.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		pain.Position = UDim2.new(0.00185304531, 0, 0.470196843, 0)
		pain.Size = UDim2.new(0, 95, 0, 49)
		pain.Font = Enum.Font.ArialBold
		pain.Text = "Mass Pain Inflection (T) Must Be A Witch"
		pain.TextColor3 = Color3.fromRGB(255, 85, 255)
		pain.TextScaled = true
		pain.TextSize = 14.000
		pain.TextWrapped = true
		pain.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'T'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "AdvancedInflict", 
							[2] = mouse.Hit.p
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)


		reset.Name = "reset"
		reset.Parent = main
		reset.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		reset.Position = UDim2.new(0.723412991, 0, 0.909473777, 0)
		reset.Size = UDim2.new(0, 53, 0, 42)
		reset.Font = Enum.Font.PermanentMarker
		reset.Text = "Respawn"
		reset.TextColor3 = Color3.fromRGB(85, 170, 255)
		reset.TextScaled = true
		reset.TextSize = 14.000
		reset.TextWrapped = true
		reset.MouseButton1Down:connect(function()
			game:GetService("ReplicatedStorage").Events.Respawn:FireServer()
		end)


		teleport.Name = "teleport"
		teleport.Parent = main
		teleport.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		teleport.Position = UDim2.new(0.499262363, 0, 0.258947372, 0)
		teleport.Size = UDim2.new(0, 96, 0, 50)
		teleport.Font = Enum.Font.ArialBold
		teleport.Text = "Phasmatos Lactus (P) Must Be A Witch"
		teleport.TextColor3 = Color3.fromRGB(255, 85, 255)
		teleport.TextSize = 14.000
		teleport.TextWrapped = true
		teleport.MouseButton1Down:connect(function()
			local Player = game.Players.LocalPlayer
			local Character = Player.Character
			local Humanoid = Character.Humanoid
			local UserInputService = game:GetService("UserInputService")
			local mouse = Player:GetMouse()
			--local Debounce = true
			local Key = 'P'
			local db = true

			UserInputService.InputBegan:Connect(function(input, IsTyping)
				if IsTyping then return end
				if input.KeyCode == Enum.KeyCode[Key] then
					local A_1 = "Magic"
					local A_2 = 
						{
							[1] = "Teleport", 
							[2] = mouse.Hit.p
						}
					local Event = game:GetService("ReplicatedStorage").Events.Witch
					Event:FireServer(A_1, A_2)

				end
			end)
		end)

		bite.Name = "bite"
		bite.Parent = main
		bite.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		bite.Position = UDim2.new(0.499262363, 0, 0.772631586, 0)
		bite.Size = UDim2.new(0, 96, 0, 50)
		bite.Font = Enum.Font.ArialBold
		bite.Text = "WereWolf Bite(U) Must Be A Vamp"
		bite.TextColor3 = Color3.fromRGB(170, 0, 0)
		bite.TextSize = 14.000
		bite.TextWrapped = true
		bite.MouseButton1Down:connect(function()
			local LocalPlayer = game.Players.LocalPlayer
			local Character = LocalPlayer.Character
			local Humanoid = Character.Humanoid
			local Mouse = LocalPlayer:GetMouse()
			local Werewolf = game:GetService("ReplicatedStorage").Events.Werewolf

			game:GetService("UserInputService").InputBegan:Connect(function(Input, isTyping)
				if isTyping then return end
				if Input.KeyCode == Enum.KeyCode.U and Mouse.Target then
					local Target = Mouse.Target.Parent:FindFirstChild("Humanoid") or Mouse.Target.Parent.Parent:FindFirstChild("Humanoid")
					if Target then
						local Player = game:GetService("Players"):GetPlayerFromCharacter(Target.Parent)
						Werewolf:FireServer("Bite", {false, Player.Character})
					end
				end
			end)
		end)



		TextLabel_3.Parent = main
		TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel_3.BackgroundTransparency = 1.000
		TextLabel_3.Position = UDim2.new(0.0134136807, 0, 0.153684214, 0)
		TextLabel_3.Size = UDim2.new(0, 195, 0, 50)
		TextLabel_3.Font = Enum.Font.PatrickHand
		TextLabel_3.Text = "Witches"
		TextLabel_3.TextColor3 = Color3.fromRGB(255, 85, 255)
		TextLabel_3.TextScaled = true
		TextLabel_3.TextSize = 14.000
		TextLabel_3.TextWrapped = true

		vervain.Name = "vervain"
		vervain.Parent = main
		vervain.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		vervain.Position = UDim2.new(0.499262363, 0, 0.574736893, 0)
		vervain.Size = UDim2.new(0, 96, 0, 49)
		vervain.Font = Enum.Font.ArialBold
		vervain.Text = "Vervain Skin (Must Be A Witch)"
		vervain.TextColor3 = Color3.fromRGB(255, 85, 255)
		vervain.TextSize = 14.000
		vervain.TextWrapped = true
		vervain.MouseButton1Down:connect(function()
			local args = {
				[1] = "Magic",
				[2] = {
					[1] = "VervainBody",
					[2] = game:GetService("Players").LocalPlayer.Character
				}
			}

			game:GetService("ReplicatedStorage").Events.Witch:FireServer(unpack(args))
		end)

		TextLabel_4.Parent = main
		TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel_4.BackgroundTransparency = 1.000
		TextLabel_4.Position = UDim2.new(-0.00279770512, 0, 0.667368412, 0)
		TextLabel_4.Size = UDim2.new(0, 195, 0, 50)
		TextLabel_4.Font = Enum.Font.PatrickHand
		TextLabel_4.Text = "Vampires"
		TextLabel_4.TextColor3 = Color3.fromRGB(170, 0, 0)
		TextLabel_4.TextScaled = true
		TextLabel_4.TextSize = 14.000
		TextLabel_4.TextWrapped = true

		TextLabel_5.Parent = main
		TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel_5.BackgroundTransparency = 1.000
		TextLabel_5.Position = UDim2.new(0.10560815, 0, 0.835789382, 0)
		TextLabel_5.Size = UDim2.new(0, 151, 0, 50)
		TextLabel_5.Font = Enum.Font.PatrickHand
		TextLabel_5.Text = "Extras"
		TextLabel_5.TextColor3 = Color3.fromRGB(85, 170, 255)
		TextLabel_5.TextScaled = true
		TextLabel_5.TextSize = 14.000
		TextLabel_5.TextWrapped = true
		
	end
end)
