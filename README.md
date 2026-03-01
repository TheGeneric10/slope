## SLOPE

SLOPE is a fast-paced neon arcade runner built with a single-page HTML5 Canvas stack. You steer through a narrowing futuristic track, collect gems, chain combos, and survive escalating hazards while dynamic effects, powerups, and responsive controls keep each run intense.

The project is designed to be lightweight and easy to run locally with no build step. Core gameplay systems include endless and adventure modes, rotating quest objectives, unlockable cosmetics, powerup-driven strategy, and menu/HUD flows tailored for both keyboard and touch devices.

This repository contains the complete game implementation (`index.html`) along with static assets and styles. It is intended for quick iteration, visual polish, and gameplay tuning in a compact codebase that can be hosted as simple static files.

## Local development

- Start a static file server from the repository root (any simple static server works):

```bash
python -m http.server 8000
```

- Open `http://localhost:8000` in your browser.

## Quality checks

Run the repository test script to syntax-check inline JavaScript embedded in `index.html`:

```bash
npm test
```
