# Slow Seas 🌊⛵

**Slow Seas** is an interactive 3D maritime simulation built with **Three.js**. Control your boat, explore the ocean, and enjoy an immersive visual and audio environment with day/night cycles and dynamic weather.

---

## Demo & Controls

- Boat movement: **W/A/S/D** or **Arrow keys**
- Pause: **P**
- Switch camera: **C**
- Toggle sound: **M**
- Top panel for quick actions and navigation metrics.

![Minimap and UI](screenshot.png)

---

## Features

- **Realistic 3D Environment**
  - Water with reflection, distortion, and wave effects using `Three.js Water`.
  - Dynamic sky with weather presets and day/night cycle (`Three.js Sky`).

- **Detailed Boat**
  - Hull, cabin, masts, animated sails, and flag with natural movement.
  - Boat trail displayed on the minimap.

- **Immersive Audio**
  - Ambient sea sounds and background music.
  - Procedural fallback if remote assets fail to load.

- **Responsive UI**
  - Metrics for speed, distance, and time.
  - Minimap with boat trail.
  - Control panel for pausing, camera, weather, and sound.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/slow-seas.git
cd slow-seas
