# Pedro Esteves — Game Prototypes & AI Experiments

👋 Hi, I'm Pedro  
🌍 Barcelona • 🎯 AI Learner • 🧗 Climber

I build small, fast game prototypes and automation/AI experiments. Below are my current playable projects with live demos and a quick tech/feature snapshot.

---

## 🎮 Projects

### 1) Pulse Drive — low-poly 3D racer (WebGL) - Very early development, not fully functioning yet.
**Live:** (https://esteves7771.github.io/Pulse-Drive)  
**What it is:** Lightweight arcade racer with procedural tracks, bots, and a responsive chase cam.  
**Notable features**
- Three.js renderer with fog/lighting + sky dome
- Procedural track baking (straights/arcs/switchbacks), curvature/banking arrays
- Simple vehicle physics (longitudinal/lateral velocity, steer filtering)
- Bot AI with look-ahead path following & curvature-aware speed target
- LocalStorage for settings & best laps, in-game HUD/minimap
- Mobile touch HUD + keyboard/gamepad input
- Two-track music system with crossfade

**Tech:** JavaScript (ES modules), Three.js, Canvas textures, LocalStorage

---

### 2) MataTudo — top-down arena shooter (HTML5)
**Live:** https://esteves7771.github.io/MataTudo/  
**What it is:** A wave/level-based shooter with bosses and daily/weekly goals.  
**Notable features**
- Start/Pause/Restart flow with on-screen UI
- Level-ups every 30 kills; periodic boss spawns (shown in UI)
- Music toggle + volume, “Tips” pane for controls
- Local leaderboards + “Hall of Fame” stored in browser
- Daily/weekly missions panel with progress and rewards

**Tech:** JavaScript, HTML/CSS, LocalStorage (leaderboards & progress)  
*(All UI elements and mission/leaderboard text visible in the live build.)* :contentReference[oaicite:0]{index=0}

<img width="2277" height="1082" alt="image" src="https://github.com/user-attachments/assets/1407392f-c257-4603-ae3c-feb8cdb1791b" />

---

### 3) Pixel Outrider — 2D action/platformer (HTML5)
**Live:** https://esteves7771.github.io/Pixel-Outrider/  
**What it is:** Side-scroller with jumping, dashing, charged beam, and periodic bosses.  
**Notable features**
- HUD (HP, Score, Coins, Distance)
- Keyboard + mouse controls: move/jump/shoot, RMB/Q charge beam, Shift dash
- Pause & Music toggle; optional “Night” mode; dev “H” debug hint in UI
- 3 lives with respawn, HP packs, boss about every ~600 tiles

**Tech:** JavaScript, HTML/CSS  
*(All controls and mechanics listed on the page UI.)* :contentReference[oaicite:1]{index=1}

<img width="2544" height="1253" alt="image" src="https://github.com/user-attachments/assets/361aeed4-b8a7-4616-869e-8a44d4f4c814" />

---

## 🧰 Skills I’m actively using (honest list)

- **Game loops & state management:** menu → select → race/play → pause/results
- **Input systems:** keyboard, mouse, touch (and gamepad on Pulse Drive)
- **3D & WebGL:** Three.js scene setup, fog/lighting, sky domes, instanced props
- **Procedural generation:** track baking, curvature/banking, prop scattering (Pulse Drive)
- **Lightweight physics & AI:** vehicle kinematics, steer filtering, look-ahead path following
- **UI/HUD design:** in-game overlays, minimap, mission panels, settings toggles
- **Persistence:** LocalStorage (settings, bests, leaderboards)
- **Audio:** music crossfades, mute/volume toggles
- **Performance basics:** low-poly meshes, canvas textures, simple materials

---

## 🚀 How to run locally

```bash
# clone your repo then:
# serve with any static server
python3 -m http.server 8080
# or
npx serve .
