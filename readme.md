```lua
function loadprofile()
  local Name = "Barnacle"
  local Website_You_Should_Check_Out = "barnical.github.io"
  local maingithub = "github.com/Tropxzz"
  local t = {maingithub, Website_You_Should_Check_Out, Name}
  return t
end

for i,v in pairs(loadprofile()) do
  print(v)
end

print("Success")
```
