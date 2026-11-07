<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:1c1c1c,100:000000&height=130&section=header&text=COMPLETEXYZ&fontSize=46&fontColor=ffffff&fontAlign=50&fontAlignY=40&desc=%5B%20D%20E%20V%20%5D&descSize=16&descAlign=50&descAlignY=68&stroke=ffffff&strokeWidth=1" width="100%" alt="Completexyz" />

</div>

<br>

```lua
local Players = game:GetService("Players")

local Developer = {}
Developer.__index = Developer

function Developer.new(info)
    return setmetatable(info, Developer)
end

function Developer:greet(player)
    print(`Welcome {player.Name}, I'm {self.name}`)
    print(`Stack: {table.concat(self.stack, ", ")}`)
end

local me = Developer.new({
    name       = "Completexyz",
    university = "KMITL, Computer Science",
    school     = "Debsirin School",
    stack      = { "Lua", "JavaScript", "Java", "C", "Python" },
})

Players.PlayerAdded:Connect(function(player)
    me:greet(player)
end)
```

<br>

<div align="center">

### `stack`

<table>
<tr>
<td align="center"><sub><code>LANGUAGES</code></sub></td>
<td>

![Lua](https://img.shields.io/badge/Lua-21262d?style=flat-square&logo=lua&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-21262d?style=flat-square&logo=javascript&logoColor=white)
![Java](https://img.shields.io/badge/Java-21262d?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-21262d?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-21262d?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td align="center"><sub><code>WEB</code></sub></td>
<td>

![Node.js](https://img.shields.io/badge/Node.js-21262d?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-21262d?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-21262d?style=flat-square&logo=react&logoColor=white)

</td>
</tr>
<tr>
<td align="center"><sub><code>TOOLS</code></sub></td>
<td>

![Git](https://img.shields.io/badge/Git-21262d?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-21262d?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-21262d?style=flat-square&logo=visualstudiocode&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-21262d?style=flat-square&logo=discord&logoColor=white)

</td>
</tr>
</table>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:1c1c1c,100:000000&height=40&section=footer" width="100%" alt="" />

</div>
