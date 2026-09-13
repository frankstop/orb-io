# Orb.io

A fast, neon-lit arena game built entirely in one HTML file. Grow your orb by absorbing pellets and rival cells, split to attack, eject mass strategically, and climb the live leaderboard.

**[Play Orb.io](https://frankiejvaldez.com/orb-io/)**

## Features

- Instant browser play with no installation or build step
- Smooth HTML5 Canvas rendering and camera movement
- 28 autonomous opponents with distinct behaviors
- Splitting, merging, mass ejection, hazards, and particle effects
- Live leaderboard, player stats, and radar minimap
- Custom nicknames, color themes, and orb emblems
- Responsive desktop and touch controls
- Procedural Web Audio sound effects with a persistent mute setting
- Spatial-grid collision optimization for a busy arena

## Controls

| Action | Desktop | Touch |
| --- | --- | --- |
| Move | Aim with the mouse | Drag toward your target |
| Split | `Space` | **Split** button |
| Eject mass | Hold `W` | Hold **Eject** |
| Toggle sound | `M` or the sound button | Sound button |

## Run locally

No dependencies are required. Open `index.html` directly, or serve the folder with any static web server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Tech

- HTML5 Canvas
- Vanilla JavaScript
- CSS
- Web Audio API
- Local storage

## Deployment

The game is deployed from the `main` branch with GitHub Pages.

## License

MIT
