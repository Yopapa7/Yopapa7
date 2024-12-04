local args = {
    [1] = "Tiredless"
}

local abilityEvent = game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Knit"):WaitForChild("Services"):WaitForChild("AbilityService"):WaitForChild("RE"):WaitForChild("Ability")

while true do
    abilityEvent:FireServer(unpack(args))
    task.wait(3)
end
