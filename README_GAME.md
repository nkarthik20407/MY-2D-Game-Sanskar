# Playable 2D Adventure Shooter

This repository contains a single-file playable prototype of a 2D platformer shooter.

Files:
- `index.html` — Playable game. Open in a modern browser.
- `2D game.html` — Original prototype (kept for reference).

How to run:
- Double-click `index.html` in Windows Explorer to open in your default browser.
- Or run a local HTTP server (recommended) from the project folder. With Python 3:

```powershell
# from the project directory
python -m http.server 8000; Start-Process "http://localhost:8000/index.html"
```

Controls:
- Desktop: Arrow keys / A D to move, W / Space to jump, K to shoot.
- Mobile: Use on-screen buttons.

Notes:
- This is a small demo. You can customize level platforms, spawn rates, and player/enemy stats inside `index.html`.
