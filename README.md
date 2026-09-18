# The Systems Engineer — Interactive Résumé

An interactive, shonen-manga styled résumé for **Magnim Maxime AWILI** — Senior Software Engineer / Technical Lead — complete with a playable mini-game, **Zero Downtime**.

**Live:** https://magmax.space

The portfolio covers backend engineering, distributed systems, DevOps, cloud platforms, reliability, security and technical leadership, with concrete examples from EPI Wero payment services and developer tooling. Availability and latency figures describe design requirements.

## Features
- Illustrated manga cover, three-panel opening sequence, character sheet, signature techniques, career chapters, training arc, and side quests.
- **Recruiter Mode** toggle for a clean, printable version
- **Zero Downtime: Paris Run** — an illustrated rooftop runner with a sunset skyline, a red-scarf engineer, and nine French landmarks, including Notre-Dame, the Panthéon, Mont Saint-Michel and Chenonceau.
- Dodge bug and production-incident bombs that damage uptime, plus flaky tests, tech debt and merge conflicts that slow the run for three seconds. Landmarks alternate with hazards; technology pickups restore uptime.
- Play through real career checkpoints from Société Générale to Transactis. Collect the technologies of each chapter to earn points and restore uptime, then unlock endless Paris.
- Three difficulty levels, double jumps, keyboard/touch controls, pause, and a locally saved personal best.
- Static HTML/CSS/JavaScript with local cover artwork in `assets/`; no build step.

Just open `index.html` in any modern browser.

The cover uses an original manga architect avatar with ink, screentone, a red scarf, and Strasbourg-inspired rooftops. The optimized WebP is approximately 619 KB; the editable source is retained in `assets/`.

Game controls: **Space / ↑ / W / tap** to jump, again in the air to double-jump, **P** to pause, **R** to restart, and **Esc** to return to the résumé. The game also pauses when the browser loses focus. All game artwork is drawn directly on canvas; no extra assets or dependencies are needed.
