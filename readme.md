```
  ██████╗  █████╗ ██████╗ ███████╗██╗      ██████╗ ███████╗
  ██╔══██╗██╔══██╗██╔══██╗██╔════╝██║     ██╔═══██╗██╔════╝
  ██████╔╝███████║██████╔╝█████╗  ██║     ██║   ██║███████╗
  ██╔══██╗██╔══██║██╔══██╗██╔══╝  ██║     ██║   ██║╚════██║
  ██████╔╝██║  ██║██████╔╝███████╗███████╗╚██████╔╝███████║
  ╚═════╝ ╚═╝  ╚═╝╚═════╝ ╚══════╝╚══════╝ ╚═════╝ ╚══════╝
                     [ TERMINAL EDITION ]
```

> `[ SYSTEM STATUS: ONLINE ]` `[ DATABASE INTEGRITY: 100% ]` `[ SIGNAL: STRONG ]`
> 
> An infinite archive of every possible tune, picture, program, and world.
> Accessible via unique base-62 address fragments.

---

## > PROTOCOL_OVERVIEW

**Babel-OS** is a terminal-themed reconstruction of the Babel Gallery project. Every piece in the library — a tune, a picture, a program, a galaxy — is generated entirely in the browser from a unique address. Nothing is stored on a server. Every number maps to exactly one piece, and every piece maps back to exactly one number.

This edition reimagines the interface as a **military-grade data recovery terminal**: CRT scanlines, phosphor green text, glitch effects, and telemetry panels. The content is exactly the same. The feeling is very different.

```
> INSPIRATION:  BORGES, J.L. — "The Library of Babel" (1941)
> ARCHITECTURE: MIXED-RADIX + BIJECTIVE SCRAMBLE + BASE-62
> RUNTIME:      BROWSER-ONLY. NO SERVER. NO BUILD. NO DEPS.
> LICENSE:      MIT
```

---

## > SECTOR_MANIFEST

| SECTOR ID | FILE | DESCRIPTION | LIBRARY SIZE |
|:---|:---|:---|:---|
| `INDEX` | `index.html` | Central terminal hub + daily recovered fragment | — |
| `AUDIO_ARRAY` | `music.html` | Synthesizer, drum machine, 32-step piano-roll | ~10⁸⁴ |
| `VISUAL_MATRIX` | `image.html` | Pixel grids from 16×9 to 80×45 | ~10³²⁵¹ |
| `SCRIPTORIUM` | `code.html` | 8 languages × 16 concepts × 4 styles | ~10⁸ |
| `BIO_SIM` | `ecosystem.html` | Keyframe + cellular automata animation | ~3.2×10⁶⁰ |
| `OCEANIC_PROBE` | `aquarium.html` | Interactive fish, plants, sonar | ~3×10²² |
| `DEEP_SPACE` | `galaxy.html` | Spiral, elliptical, ring galaxies | ~1.7×10²⁰ |
| `MULTI_VIEW` | `pair.html` | 2–6 galleries side by side | — |
| `ARCHIVE` | `finds.html` | Community finds via GitHub Issues | — |
| `DIAGNOSTICS` | `stats.html` | System telemetry + full statistics | — |

---

## > HOW_THE_LIBRARY_WORKS

```
> STEP 01 // MIXED-RADIX ENCODING
  Each piece is a list of digits. Each parameter has its own base.
  The product of all bases = TOTAL, the size of the library.

> STEP 02 // BIJECTIVE SCRAMBLE
  y = (a·x + c) mod M        where a is coprime to M
  This spreads neighbouring numbers across very different pieces.
  The inverse is exact, so editing a piece recovers its address.

> STEP 03 // BASE-62 ADDRESSING
  0–9  A–Z  a–z      →  ~45% shorter than decimal, still exact

> STEP 04 // DETERMINISTIC RENDERING
  The address is decoded back into parameters.
  Those parameters are rendered with Web Audio / Canvas 2D.
```

**No two pieces share an address.** **No two addresses share a piece.** This is the entire architecture.

---

## > SECTOR_DETAILS

### `AUDIO_ARRAY` — Music
- 14 sound parameters, 32-step drum & melody grids
- 16 presets, live spectrum visualizer
- Synthesized with Web Audio API (no samples)

### `VISUAL_MATRIX` — Images
- 3 color modes (mono, gray, 16-color), 5 cell sizes
- Paint mode enabled, PNG export

### `SCRIPTORIUM` — Code
- 8 languages × 16 concepts × 4 styles
- Live execution via Judge0 CE API
- Download with correct file extension

### `BIO_SIM` — Ecosystem
- 201 bits across 37 parameters
- Keyframe base + Cellular Automata overlay
- Timeline bar, WebM/GIF export

### `OCEANIC_PROBE` — Aquarium
- 23 parameters (fish, plants, water, light)
- Interactive (click to feed), ambient sonar sound

### `DEEP_SPACE` — Galaxy
- 19 parameters (type, arms, stars, nebulae)
- Full rotation, radar sweep overlay

### `MULTI_VIEW` — Multi-Panel
- View 2–6 galleries side by side
- One shared address across all panels
- Adapts to screen size

### `ARCHIVE` — Finds
- Community discoveries via GitHub Issues
- Requires `approved` label by maintainer

### `DIAGNOSTICS` — Stats
- Full system logs, parameter breakdowns, fun facts

---

## > RUNNING_LOCALLY

No build step. No dependencies. Clone and open.

```bash
$ git clone https://github.com/sajadshahimn/babel-os.git
$ cd babel-os
$ python3 -m http.server 8080
# OR open index.html directly in a browser
```

---

## > DEPLOYMENT

Designed for **GitHub Pages**:

1. Push to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch** → `main` → `/ (root)`
4. Save. Live at `https://USERNAME.github.io/babel-os/`

---

## > KEYBOARD_SHORTCUTS

| Shortcut | Action |
|:---|:---|
| `R` | Random address |
| `←` `→` | Previous / next address |
| `C` | Copy current address |
| `Space` | Pause/play (audio, animation) |
| `S` | Toggle sound |
| `Ctrl+Enter` | Run code (scriptorium) |

---

## > PHILOSOPHY

> "The Library is unlimited and cyclical."
> — Jorge Luis Borges

Every gallery in Babel-OS is a **bijection**: an exact one-to-one mapping between integers and pieces. A single number — `A3f9K2m` — is not a shortcut. It is **the piece itself**, expressed in base-62.

- **No storage is required.**
- **No two pieces are the same.**
- **Nothing is lost.** The scramble is invertible.
- **The address is the content.**

Babel-OS doesn't ask "what shall we create?" It asks "**what number shall we decode?**"

---

## > LICENSE

MIT License. Copyright (c) 2026 Mehrzad.
See [LICENSE](LICENSE) for full text.

```
> END OF FILE
> SYS.VER: 2.0.26
> PROTOCOL: BORGES
> [ YOU ARE NOW INSIDE THE LIBRARY. ]
```
