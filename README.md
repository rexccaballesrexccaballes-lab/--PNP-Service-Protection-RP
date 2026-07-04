script.Parent.Touched:Connect(function(hit)
    if hit.Parent:FindFirstChild("Humanoid") then
        script.Parent.Transparency = 0.5
        script.Parent.CanCollide = false
        wait(2)
        script.Parent.Transparency = 0
        script.Parent.CanCollide = true
    end
end)

