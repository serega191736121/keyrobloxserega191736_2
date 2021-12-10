script.Parent.Touched:connect(function(p)
if p.Parent.Name == "Key" then <Имя твоего ключа
script.Parent.Transparency = 0.5
script.Parent.CanCollide = false
wait(1)
script.Parent.Transparency = 0
script.Parent.CanCollide = true
end
end)

