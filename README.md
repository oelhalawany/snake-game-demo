# 🐍 Snake Game Demo

A pure HTML5/CSS/JavaScript Snake game. No frameworks, no assets, no build step — one file.

**Play it:** https://oelhalawany.github.io/snake-game-demo/

> **Disclaimer:** This is a non-commercial demo project made for learning purposes only. It is not affiliated with or endorsed by any existing game or its rights holders. All code and graphics here were written from scratch for this project.

## Features

- 🐍 Classic Snake with wrap-around walls
- ⚡ Speeds up as your score grows
- 🏆 Persistent best score (localStorage)
- 📱 Mobile-friendly — on-screen D-pad on touch devices
- 🎨 Everything drawn with Canvas (no image files)

## Controls

| Input | Action |
| ----- | ------ |
| ↑ ↓ ← → or W A S D | Change direction |
| D-pad (touch) | Change direction |

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub (branch `main`).
2. Repo → **Settings** → **Pages**.
3. Under **Source**, pick **Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
4. Wait ~1 minute, then open `https://<username>.github.io/snake-game-demo/`.
