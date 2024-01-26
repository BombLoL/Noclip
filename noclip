--[[
Made by BombLoL (def not copied)
made this in roblox studio
it only targets your head not your hpr, cuz if hpr then broken
thx (give credit if u want to copy)
--]]
local player = game:GetService("Players").LocalPlayer
local Players = game:GetService("Players")
local head = player.Character:FindFirstChild("Head")
local hpr = player.Character:FindFirstChild("HumanoidRootPart")
local hum = player.Character:FindFirstChildOfClass("Humanoid")
function noclipFunction()
	head.Touched:Connect(function(hit)
		if hit:IsA("Part", "MeshPart") then
			if hit.CanCollide == true then
				hit.CanCollide = false
				task.wait(0.5)
				hit.CanCollide = true
				hum.Health = hum.MaxHealth
			end
		end
	end)
end
noclipFunction()
Players.PlayerAdded:Connect(noclipFunction) -- idfk what dis do
