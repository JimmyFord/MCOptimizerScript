# 🌍 WorldOptimizer

WorldOptimizer is a lightweight Paper / Spigot plugin designed to improve server performance by reducing unnecessary entity load in unused areas of the world.

## ✨ Features
- 🗑️ Automatically removes dropped items after a configurable time
- 🧟 Prevents mobs from spawning far away from players
- ⚡ Minimal performance impact
- 🔧 Fully configurable

## 📦 Requirements
- Java 17+
- Paper or Spigot
- Minecraft 1.20+

## 🚀 Installation
1. Download or build the plugin JAR
2. Place it in your server's `plugins` folder
3. Restart the server
4. Configure `config.yml` if needed

## ⚙️ Configuration
```yaml
item-cleanup:
  max-age-ticks: 6000
  check-interval-ticks: 600

mob-spawn-control:
  enabled: true
  max-distance-from-player: 64
