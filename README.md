<center><img src="https://i.postimg.cc/MKPVVR1s/dplogo-512.png" alt="logo"></center>
<center><img src="https://i.postimg.cc/RZ9dqPFx/introduce.png" alt="introduce"></center>

DP-RewardChest is a **reward chest plugin** that allows players to open special chests using keys and receive random rewards.  
Each chest can be customized with its own reward pool, random logic, and visual opening effects.

---

<center><img src="https://i.postimg.cc/RZ9dqP08/description.png" alt="description"></center>

- Create multiple **reward chests**, each with unique rewards  
- Use **key items** to open reward chests  
- Supports **random** and **weighted random** reward selection  
- Fully configurable reward inventories via **GUI editor**  
- Displays **visual item animation** when opening chests  
- All reward chest data is saved automatically  

---

<center><img src="https://i.postimg.cc/rwcjzhpH/depend-plugin.png" alt="depend-plugin"></center>

- All DP-Plugins require the **`DPP-Core`** plugin  
- The plugin will not work if **`DPP-Core`** is not installed  
- You can download **`DPP-Core`** here: <a href="https://github.com/DP-Plugins/DPP-Core/releases" target="_blank">Click me!</a>  
- No economy or PlaceholderAPI dependency required  

---

<center><img src="https://i.postimg.cc/dV01RxJB/installation.png" alt="installation"></center>

1️⃣ Place the **`DPP-Core`** plugin and this plugin file (**`DP-RewardChest-*.jar`**) into your server’s **`plugins`** folder  

2️⃣ Restart the server, and the plugin will be automatically enabled  

3️⃣ Configure reward chests and keys using in-game commands  

---

<center><img src="https://i.postimg.cc/jSKcC85K/settings.png" alt="settings"></center>

- **`config.yml`**  
  - Default reward animation offset  
  - Plugin message settings  

- Reward chest data is managed automatically through GUI and commands  

---

<center><img src="https://i.postimg.cc/SxqdjZKw/command.png" alt="command"></center>

❗ Some commands require admin permission (`dprc.admin`)

**Command List and Examples**

| Command | Permission | Description | Example |
|---|---|---|---|
| `/dprc create <name>` | dprc.admin | Create reward chest | `/dprc create Treasure` |
| `/dprc delete <name>` | dprc.admin | Delete reward chest | `/dprc delete Treasure` |
| `/dprc items <name>` | dprc.admin | Edit reward items | `/dprc items Treasure` |
| `/dprc maxpage <name> <page>` | dprc.admin | Set max pages | `/dprc maxpage Treasure 3` |
| `/dprc randomType <name> <SIMPLE/WEIGHTED>` | dprc.admin | Set random type | `/dprc randomType Treasure WEIGHTED` |
| `/dprc weight <name>` | dprc.admin | Set reward weights | `/dprc weight Treasure` |
| `/dprc key <name>` | dprc.admin | Set key item | `/dprc key Treasure` |
| `/dprc givekey <name> (player)` | dprc.admin | Give key item | `/dprc givekey Treasure Steve` |
| `/dprc block <name>` | dprc.admin | Set chest block | `/dprc block Treasure` |
| `/dprc reload` | dprc.admin | Reload plugin | `/dprc reload` |

**❗Notes when using commands**

- Chest names must not contain spaces  
- Keys are consumed when opening a chest  
- Reward selection follows configured random logic  
- Admin commands require **OP** or `dprc.admin` permission  

---

<center><img src="https://i.postimg.cc/Z5ZH0fqL/api-integration.png" alt="api-integration"></center>

- No external API integrations are used

---

<center><a href="https://discord.gg/JnMCqkn2FX"><img src="https://i.postimg.cc/4xZPn8dC/discord.png" alt="discord"></a></center>

- https://discord.gg/JnMCqkn2FX  
- Join our Discord for support, bug reports, or feature requests  
- Suggestions and feedback are always welcome!

---
