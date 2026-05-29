# 🧟 Survive

> A 2D post-apocalyptic side-scrolling survival game built with Unity and C#.

![Unity](https://img.shields.io/badge/Unity-6000.0f1-black?logo=unity)
![Language](https://img.shields.io/badge/Language-C%23-239120?logo=csharp)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Mac-blue)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)

---

## 🎮 About

**Survive** is a 2D horizontal side-scrolling game set in a post-apocalyptic world. The player must navigate through a long, devastated street — fending off relentless waves of zombies — in a desperate search to rescue their missing friends before it's too late.

---

## 🕹️ Gameplay

- Navigate through a procedurally generated post-apocalyptic street
- Fight off waves of zombies using melee and ranged combat
- Rescue 4 missing friends hidden throughout the world
- Survive as long as possible — every second counts

---

## ✨ Features

- Smooth horizontal side-scrolling with multi-layer parallax background
- Melee and ranged combat system
- Zombie AI with detection, chase, and attack behaviour
- Dynamic zombie wave spawning system
- Friend NPC rescue system
- Health, ammo, survival timer, and friends HUD
- Main Menu, Game Over, Loading Screen, and Victory scenes
- Post-apocalyptic street environment with procedural segment generation

---

## 🗂️ Project Structure

```
Assets/
└── _Project/
    ├── Scripts/
    │   ├── Player/
    │   │   ├── PlayerController.cs
    │   │   ├── PlayerHealth.cs
    │   │   └── PlayerCombat.cs
    │   ├── Enemies/
    │   │   ├── ZombieController.cs
    │   │   ├── ZombieHealth.cs
    │   │   └── ZombieSpawner.cs
    │   ├── Friends/
    │   │   ├── FriendNPC.cs
    │   │   └── FriendManager.cs
    │   ├── World/
    │   │   ├── ParallaxLayer.cs
    │   │   ├── ScrollingWorld.cs
    │   │   ├── CameraController.cs
    │   │   └── WorldManager.cs
    │   ├── UI/
    │   │   ├── HUDManager.cs
    │   │   └── GameOverScreen.cs
    │   └── Core/
    │       ├── GameManager.cs
    │       ├── AudioManager.cs
    │       ├── GameOverData.cs
    │       ├── LoadingScreenData.cs
    │       └── SurvivalTimer.cs
    ├── Prefabs/
    │   ├── Player/
    │   ├── Enemies/
    │   ├── Friends/
    │   └── World/
    ├── Animations/
    ├── Sprites/
    ├── Audio/
    ├── Scenes/
    │   ├── MainMenu.unity
    │   ├── GameScene.unity
    │   ├── GameOver.unity
    │   └── LoadingScreen.unity
    └── ScriptableObjects/
```

---

## 🛠️ Built With

- [Unity 6](https://unity.com/) `6000.0f1`
- C# / .NET
- Unity 2D Physics
- TextMeshPro

---

## 🚀 Getting Started

### Prerequisites
- Unity Hub installed
- Unity Editor `6000.0f1` or later
- Git

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/AtlaseraLtd/survive.git
   ```

2. Open **Unity Hub**

3. Click **Add** → select the cloned `survive/` folder

4. Open the project in Unity `6000.0f1`

5. In the **Project** panel, navigate to `Assets/_Project/Scenes/` and open `MainMenu.unity`

6. Press **▶ Play** to run the game in the Editor

---

## 🎯 Controls

| Action | Key |
|--------|-----|
| Move | `WASD` / Arrow Keys |
| Jump | `Space` |
| Melee Attack | `Left Click` / `Fire1` |
| Ranged Attack | `Right Click` / `Fire2` |

---

## 🗺️ Scenes

| Scene | Description |
|-------|-------------|
| `MainMenu` | Title screen with settings and credits |
| `GameScene` | Main gameplay — the post-apocalyptic street |
| `GameOver` | Death screen with stats and retry option |
| `LoadingScreen` | Async loading screen with survival tips |

---

## 🧟 Enemies

| Enemy | Health | Speed | Damage |
|-------|--------|-------|--------|
| Zombie | 50 | 1.8 | 10 |

More enemy types coming soon.

---

## 👥 Friends to Rescue

| Name | Location |
|------|---------|
| Alex | Early street — X: 50 |
| Sara | Mid street — X: 120 |
| Mike | Deep street — X: 220 |
| Jake | End street — X: 350 |

---

## 🛣️ Roadmap

- [x] Player movement and combat
- [x] Zombie AI and wave spawning
- [x] Friend NPC rescue system
- [x] HUD — health, timer, ammo, friends
- [x] Parallax scrolling world
- [x] Main Menu, Game Over, Loading Screen
- [ ] Sprite art and animations
- [ ] Audio — music and SFX
- [ ] Additional enemy types
- [ ] Weapon pickups
- [ ] ScriptableObject-based enemy data
- [ ] Mobile controls
- [ ] WebGL build

---

## 📄 License

This project is proprietary and owned by **Atlasera Ltd**. All rights reserved.

---

## 👨‍💻 Developed By

**Atlasera Ltd**
[github.com/AtlaseraLtd](https://github.com/AtlaseraLtd)
