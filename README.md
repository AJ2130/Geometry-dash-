# 🟨 Geometry Dash

A browser-based Geometry Dash fan game built with Scratch/TurboWarp and packaged as a single self-contained HTML file. Features a custom Geometry Dash–inspired UI theme with neon glow effects, animated loading screen, and the Orbitron font.

---

## 🎮 How to Play

1. Open `Geometry_Dash_Styled.html` in any modern web browser — no installation or server required.
2. Click the **green flag** button to launch the game.
3. Jump over obstacles and survive as long as you can!

### Controls

| Action | Input |
|--------|-------|
| Jump | `Space`, `Up Arrow`, or `Click / Tap` |
| Restart | `R` or click the green flag |

---

## ✨ Features

- **Single-file distribution** — the entire game is embedded in one `.html` file
- **Custom GD-inspired theme** — dark blue gradient background, neon blue glow, `Orbitron` font
- **Animated loading screen** — gradient progress bar with animated dot ellipsis
- **Fullscreen support** — dedicated fullscreen button built in
- **Mobile-friendly** — touch controls supported; viewport locked for consistent gameplay
- **Cloud data** — connects to TurboWarp cloud servers for global leaderboard/data features

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Game engine | [Scratch](https://scratch.mit.edu) / [TurboWarp](https://turbowarp.org) |
| Packager | [TurboWarp Packager](https://packager.turbowarp.org) |
| Runtime | TurboWarp Scaffolding (bundled) |
| Fonts | Google Fonts — Orbitron |
| Cloud | TurboWarp WebSocket cloud provider |

---

## 🚀 Running Locally

No build step needed. Just open the file:

```bash
# Option 1 — double-click the file in your file explorer

# Option 2 — serve with Python for a more accurate environment
python3 -m http.server 8080
# then visit http://localhost:8080/Geometry_Dash_Styled.html
```

---

## 📁 Project Structure

```
.
└── Geometry_Dash_Styled.html   # Complete self-contained game
```

All assets (sprites, sounds, scripts) are embedded inside the HTML file as a bundled zip — no external files are needed.

---

## 📝 Notes

- The game was originally created in Scratch and exported via the TurboWarp Packager.
- Cloud variables connect to `clouddata.turbowarp.org` — an internet connection is required for those features, but the game is otherwise fully offline.
- Canvas rendering uses `image-rendering: pixelated` for a crisp retro look.

---

## 📄 License

This project is a fan-made recreation inspired by [Geometry Dash](https://www.robtopgames.com/) by RobTop Games. It is not affiliated with or endorsed by RobTop Games.
