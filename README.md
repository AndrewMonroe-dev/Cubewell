# CUBEWELL

A 3D top-down block-dropping game in the spirit of the 1989 arcade/PC classic *Blockout*.
You look straight down into a pit and drop 3D pieces into it. A layer disappears when it is completely filled.

**Play:** https://andrewmonroe-dev.github.io/Cubewell/

## Controls

| Key | Action |
| --- | --- |
| ← → ↑ ↓ | Move piece |
| Q / W / E | Rotate around X / Y / Z |
| A / S / D | Rotate the other way |
| Space | Drop |
| G | Toggle landing ghost |
| M | Toggle sound |
| P | Pause |
| Esc | Menu |

Touch devices get on-screen buttons.

## Modes

- **Flat Fun**: 5×5×12 pit, flat pieces
- **3D Mania**: 3×3×10 pit, basic 3D pieces
- **Out of Control**: 5×5×10 pit, extended pieces including pentacubes
- **Custom**: choose width, depth, height and piece set

High scores are saved in your browser, one per pit size and piece set.

The whole game is a single `index.html` with no build step and no dependencies.
