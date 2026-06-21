# GTA Vibes

Two browser games inspired by GTA. No install, no build, just open and play.

**Play locally:** open `index.html` in any modern browser.
**Or serve:** `python3 -m http.server 8080` and visit `http://localhost:8080`.

## Games

### A · Chaos (2D, top-down)
- Single HTML file (`chaos/index.html`), no dependencies.
- Drive around a 4000x4000 grid city, hit peds, dodge cops.
- 5-star wanted system, escalating police response (more cops, faster spawn, harder fire).
- Cops shoot, ram, chase. HP bar, score, best-score persistence.
- Controls: WASD/Arrows drive · Space brake · R restart.

### B · Drift (3D, Three.js)
- Single HTML file (`drift/index.html`), Three.js loaded via CDN import-map.
- Open-world city, 16x16 block grid, low-poly buildings.
- Car physics with handbrake-induced sideways slide.
- 24 launch ramps scattered around — air time tracked.
- 4 times-of-day (Noon / Sunset / Night / Sunrise) with headlights at night.
- 3 cameras: chase / hood / top-down.
- Controls: WASD/Arrows drive · Space handbrake · C cycle camera · T cycle time · R reset.

## Tech
- Vanilla JS, zero build tooling.
- Game A: HTML5 canvas 2D.
- Game B: Three.js 0.160 via ES module import-map.
- LocalStorage for high scores / best air-time.

## Why
A quick browser-game weekend hack.
