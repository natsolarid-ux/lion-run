# 🦁 Lion Run

A browser-based endless runner game built with vanilla HTML5 Canvas. Play as a lion sprinting across the African savanna, dodging thornbushes, acacia trees, vultures, and boulders — with a dynamically shifting background that changes every 100 points.

---

## 🎮 Play

Open `lion-run.html` in any modern browser. No server, no dependencies, no installation.

---

## 🕹️ Controls

| Input | Action |
|-------|--------|
| `Space` / `↑` | Jump (press again mid-air for double jump) |
| `↓` | Duck |
| `Click` / `Tap canvas` | Jump |
| `▲ JUMP` button | Jump (on-screen) |
| `▼ DUCK` button | Duck (on-screen) |

---

## ✨ Features

### 🦁 Lion Character
- Fully hand-drawn lion with animated mane, tail tuft, and running legs
- Crouching duck pose with tail curving upward
- Small proportional legs with paw pads and claws
- Amber slit-pupil eyes and visible canine teeth

### 🌿 Lion-Themed Obstacles
- **Thornbush** — low spiky shrub, jump over it
- **Acacia Tree** — iconic flat-top umbrella canopy
- **Savanna Grass** — tall swaying grass blades with golden seed heads (single, double, triple clusters)
- **Vulture** — bald red-headed bird facing the lion; dives toward it every 100 points
- **Boulder** — mossy rounded rock with crack lines

### 🌄 Dynamic Backgrounds (changes every 100 points)
| Biome | Description |
|-------|-------------|
| ☀️ Day | Blue sky, bright sun, orange desert ground |
| 🌅 Dusk | Fiery orange sunset, red horizon |
| 🌙 Night | Dark sky, 80 twinkling stars, crescent moon with craters |
| 🌧️ Rain | Grey overcast, 60 falling rain streaks, heavy clouds |
| ❄️ Snow | Pale cold sky, falling snowflakes, snow-covered ground |

### ❤️ Lives System
- Start with **3 lives** shown as hearts in the top-left corner
- Earn **+1 life every 500 points** (max 9)
- Green sparkle burst + ascending chime when a life is gained
- Nearby obstacles are cleared after losing a life so you can recover

### 🔔 Progression
- **DING** sound every 100 points
- Speed increases every 100 points (+0.5 per level, max speed 16)
- Obstacle variety unlocks as you progress — doubles and triples appear at higher scores
- Vultures start diving at 100+ points

### 🎵 Audio
- Jump sound
- Double-jump sound
- Ding chime every 100 points (3-note ascending)
- Life-up fanfare (4-note ascending)
- All audio via Web Audio API — no external files needed

---

## 🛠️ Technical

- **Pure HTML5 Canvas** — zero dependencies, zero frameworks
- **Single file** — everything in one `.html` file, works offline
- **Web Audio API** — procedurally generated sounds
- **localStorage** — high score persists between sessions
- **Touch support** — works on mobile browsers

---

## 📁 File Structure

```
lion-run/
└── lion-run.html    # The entire game — open this in a browser
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/lion-run.git
cd lion-run
open lion-run.html   # macOS
# or just double-click the file in your file explorer
```

---

## 📸 Preview

> Day → Dusk → Night → Rain → Snow — the world shifts around you as you run

---

## 📄 License

MIT — do whatever you want with it.
