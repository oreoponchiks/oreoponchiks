<div align="center">

# 👋 Hello I'm Slider

### Roblox Scripter • Luau Developer • Game Systems Builder

![Roblox](https://img.shields.io/badge/Roblox-Studio-00A2FF?style=for-the-badge&logo=roblox&logoColor=white)
![Luau](https://img.shields.io/badge/Luau-Scripting-00A2FF?style=for-the-badge&logo=lua&logoColor=white)
![Rojo](https://img.shields.io/badge/Rojo-Workflow-E2231A?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🎮 About Me

I build gameplay systems and tools for Roblox experiences using **Luau**. I enjoy clean, modular code, secure client-server architecture, and making games that feel smooth to play.

- 🔨 Currently working on: **Scourge of Viltrum**
- 📚 Currently learning: **Advanced OOP in Luau, ECS patterns, and DataStore optimization**
- 🤝 Open to: **commissions, collabs, and team projects**
- 💬 Discord: **x60mx**
- 🎯 Fun fact: **[something fun about you]**

---

## 💻 About My Code

```lua
local Developer = {}
Developer.__index = Developer

function Developer.new(name)
	local self = setmetatable({}, Developer)
	self.Name = name
	self.Language = "Luau"
	self.Skills = {
		"Client-Server Architecture",
		"RemoteEvents & RemoteFunctions",
		"DataStore Systems",
		"OOP & Modules",
		"UI Scripting",
		"Combat Systems",
		"Tool & Plugin Development",
	}
	self.Coffee = math.huge
	return self
end

function Developer:Build(idea)
	print(("Building %s with clean, optimized code..."):format(idea))
	return true
end

local me = Developer.new("Slider")
me:Build("your next big game")
```

---

## 🛠️ Skills & Tools

| Area | What I Work With |
|------|------------------|
| **Language** | Luau (typed & untyped), Lua |
| **Core Scripting** | Services, Modules, RemoteEvents, BindableEvents, CollectionService |
| **Data** | DataStoreService, ProfileService / ProfileStore, session locking |
| **Gameplay** | Combat, inventories, shops, quests, leaderboards, pets |
| **UI** | ScreenGuis, TweenService, UI animations, responsive layouts |
| **Physics & Movement** | Raycasting, constraints, custom character controllers |
| **Workflow** | Rojo, Wally, Selene, StyLua, Git, VS Code |
| **Frameworks** | Knit, Matter (ECS), Fusion / Roact, Promise |

---

## 🚀 Featured Projects

### 🔹 Scourge of Viltrum
Short description: full combat system with hitboxes, cooldowns, and server validation).
**Tech:** Luau, RemoteEvents, Raycasting
