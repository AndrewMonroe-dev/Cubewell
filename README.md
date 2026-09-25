# BREACH.EXE

A 3D top-down block-dropping game in the spirit of the 1989 arcade/PC classic *Blockout*, reskinned as a hacking terminal.
You look straight down into a firewall and drop exploit packets into it. A firewall layer is breached when it is completely filled.
The trace meter rises as the stack grows. If it reaches the top, the trace completes and the connection is terminated.

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

### Mouse

| Mouse | Action |
| --- | --- |
| Move | Piece follows the pointer |
| Double-click | Drop |
| Scroll wheel | Spin flat (Z) |
| Right-click | Spin flat (Z) |
| Right-drag left / right | Roll sideways (Y) |
| Right-drag up / down | Tip forward / back (X) |

Pressing any key hands control back to the keyboard until the mouse moves again.

**Rotation sensitivity** (Low / Medium / High, in the menu) sets how far you right-drag per quarter-turn and the minimum pause between turns. Holding a rotate key does not auto-repeat.

Touch devices get on-screen buttons.

## Sound

All sound is synthesized live with Web Audio, so there are no audio files. It includes a dial-up modem connect, keyboard clicks, data chirps, an access-denied buzz, modem bursts when you breach a layer, trace alarms and a flatline when you get caught. Press **M** to mute.

## Modes

- **Script Kiddie**: 5×5×12 firewall, flat exploits
- **Black ICE**: 3×3×10 firewall, 3D exploits
- **Zero Day**: 5×5×10 firewall, full exploit kit including pentacubes
- **Custom Target**: choose nodes, firewall layers and exploit kit

Best hauls are saved in your browser, one per firewall size and exploit kit.

The whole game is a single `index.html` with no build step. Its only outside resources are two Google Fonts, Chakra Petch and JetBrains Mono, and it falls back to system monospace fonts if they don't load.
