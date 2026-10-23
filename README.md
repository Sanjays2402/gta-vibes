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
- **Game.** Provided for entertainment. Take breaks; it is not designed for people with photosensitive epilepsy, and flashing effects may occur.
- **Fan project.** Not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive. "GTA" and "Grand Theft Auto" are their trademarks. The project is meant to contain no Rockstar game assets; any found will be removed on request.
- **Third parties.** Names, logos, APIs, and services of others belong to their owners and are used for identification only; no affiliation or endorsement is implied.
- **Your statutory rights.** Nothing here limits rights that cannot be waived by agreement, including under consumer-protection laws in the USA, Canada (including Quebec), and India (Consumer Protection Act, 2019).
- **License.** Use, copying, and distribution are governed by the [LICENSE](LICENSE) file; if anything here conflicts with it, the license controls.

## Content, Assets & Fair Use

- **Original work.** Unless noted otherwise (including below), the code, text, design, and images in this repository were created by the author.
- **Libraries, fonts, and icons.** Third-party libraries, fonts (for example Google Fonts), and icon sets belong to their creators and are used under their own licenses; see the dependency manifests and each source for terms.
- **Logos, brands, and screenshots.** Third-party names, logos, and screenshots appear only to identify or describe their products (nominative use). They remain the property of their owners and do not imply affiliation or endorsement.
- **Ideas and inspiration.** Where this project is inspired by another product, game, or idea, it is an independent implementation. It borrows only general ideas, mechanics, or styles, which are not anyone's exclusive property, and is meant to contain no third-party code or artwork used without permission.
- **Fair use and fair dealing.** Any third-party material is used in limited ways for purposes such as education, research, review, commentary, or identification, relying on fair use in the USA (17 U.S.C. § 107), fair dealing in Canada (Copyright Act, ss. 29–29.2), and fair dealing in India (Copyright Act, 1957, s. 52), where they apply.
- **Concerns and takedown requests.** If you own rights in something here and believe it is used improperly, [open an issue](https://github.com/Sanjays2402/gta-vibes/issues) or contact the author through their GitHub profile with a link to the material and your claim. It will be reviewed promptly and credited, changed, or removed as appropriate. You may also use GitHub's DMCA process.
- **Contributions.** By contributing, you confirm you have the right to submit your contribution and agree it is licensed under this repository's license.
- **Website.** The project site has its own [Terms](https://sanjays2402.github.io/gta-vibes/terms.html) and [Fair Use](https://sanjays2402.github.io/gta-vibes/fair-use.html) pages.
