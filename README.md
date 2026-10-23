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
- Drift scoring — hold a handbrake slide to rack up drift points; best drift persists in LocalStorage.
- 4 times-of-day (Noon / Sunset / Night / Sunrise) with headlights at night.
- 3 cameras: chase / hood / top-down.
- Controls: WASD/Arrows drive · Space handbrake · C cycle camera · T cycle time · R reset.

## Tech
- Vanilla JS, zero build tooling.
- Game A: HTML5 canvas 2D.
- Game B: Three.js 0.160 via ES module import-map.
- LocalStorage for high scores / best air-time / best drift.

## Why
A quick browser-game weekend hack.

## Terms & Disclaimer

By using this project you agree to the following.

- **No warranty.** This software is provided "as is", without warranty of any kind, express or implied, including merchantability, fitness for a particular purpose, and non-infringement.
- **No liability.** To the maximum extent permitted by law, the author and contributors are not liable for any claim, loss, or damage (direct, indirect, incidental, or consequential, including lost data or profits) arising from its use.
- **Your responsibility.** You use it at your own risk and are responsible for complying with the laws that apply to you.
- **Fan project.** Not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive. "GTA" and "Grand Theft Auto" are their trademarks; no game assets are used.
- **Third parties.** Names, logos, APIs, and services of others belong to their owners and are used for identification only; no affiliation or endorsement is implied.
- **Your statutory rights.** Nothing here limits rights that cannot be waived by agreement, including under consumer-protection laws in the USA, Canada (including Quebec), and India (Consumer Protection Act, 2019).
- **License.** Use, copying, and distribution are governed by the [LICENSE](LICENSE) file; if anything here conflicts with it, the license controls.
