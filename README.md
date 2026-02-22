<div align="center">

```
████████╗███████╗████████╗██████╗ ██╗███████╗    ███████╗ ██████╗ █████╗ ██████╗ ███████╗
╚══██╔══╝██╔════╝╚══██╔══╝██╔══██╗██║██╔════╝    ██╔════╝██╔════╝██╔══██╗██╔══██╗██╔════╝
   ██║   █████╗     ██║   ██████╔╝██║███████╗    ███████╗██║     ███████║██████╔╝█████╗  
   ██║   ██╔══╝     ██║   ██╔══██╗██║╚════██║    ╚════██║██║     ██╔══██║██╔═══╝ ██╔══╝  
   ██║   ███████╗   ██║   ██║  ██║██║███████║    ███████║╚██████╗██║  ██║██║     ███████╗
   ╚═╝   ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝╚══════╝   ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝     ╚══════╝
```

**Stack blocks. Build worlds. Make the web yours.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF6B6B?style=for-the-badge&logo=webaudio&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-00fff0?style=for-the-badge)](.)

</div>

---

## ✦ What is TETRIS·SCAPE?

**TETRIS·SCAPE** is a fully self-contained, single-file web app that combines a **Tetris-style block editor** with a **live background designer** and a **full Tetris game** — all wrapped in a stunning neon retro-pixel aesthetic.

You place, rotate, and color Tetris pieces on a canvas, then "apply" them as an animated live background for your page. Save your creations to a persistent library, share them via URL, export to PNG, and customize every visual detail — fonts, colors, button sizes, UI labels — all in the browser with zero installs.

> 🎮 **Play Tetris** → 🎨 **Design with the blocks** → 🌌 **Set it as your wallpaper** → 💾 **Save it to your library**

---

## 📸 Screenshots

### 🏠 Main Editor

> The three-panel design workspace: Piece picker on the left, canvas in the center, controls on the right.

```
╔══════════════════════════════════════════════════════════════════════════════════════╗
║  ✦ TETRIS·SCAPE ✦   [📚 MY DESIGNS ②]  [🎮 PLAY TETRIS]  [⚙ SETTINGS]  [✦ CUSTOMIZE] ║
║  Stack blocks. Build worlds. Make the web yours.                                     ║
╠═════════════╦══════════════════════════════════════════════╦═══════════════════════╣
║  » PIECES   ║  » CANVAS — click to place · click to select ║  » CONTROLS           ║
║  ┌──┐ ┌──┐  ║  ┌──────────────────────────────────────┐   ║  BLOCK COLOR          ║
║  │ I│ │ O│  ║  │  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │   ║  ■ ■ ■ ■ ■ ■ ■ ■    ║
║  └──┘ └──┘  ║  │  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │   ║  [colorwheel] #00fff0 ║
║  ┌──┐ ┌──┐  ║  │  ░░░ ████ ░░░░ ███ ░░░░░░░░░░░░░░░░  │   ║  ROTATION             ║
║  │ T│ │ S│  ║  │  ░░░░░░░░ ░░░ ████ ░░░░░░░░░░░░░░░░  │   ║  [↑]  [Rotate R]      ║
║  └──┘ └──┘  ║  │  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │   ║  EDIT                 ║
║             ║  │  ░░░░░░░░░░░░░░░ ██ ░░░░░░░░░░░░░░░  │   ║  [Delete Block Del]   ║
║  THEME      ║  │  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │   ║  [Clear All]          ║
║  ● ○ ○ ○ ○  ║  └──────────────────────────────────────┘   ║  BACKGROUND           ║
║  NEON       ║                                              ║  [▶ Apply as BG]      ║
║  MUSIC      ║  PIECE: I  COLOR: ■  BLOCKS: 7  ROT: 0°     ║  [Reset BG]           ║
║  [🎵 ON]    ║                                              ║  STORAGE              ║
║  NEON 138BPM║                                              ║  [📚 Save to Library] ║
║  HISTORY    ║                                              ║  [💾 Quick Save]      ║
║  [↩UNDO][↪] ║                                              ║  [📂 Quick Load]      ║
╚═════════════╩══════════════════════════════════════════════╩═══════════════════════╝
```

---

### 🎮 Tetris Game Mode

> Full Tetris game with score tracking, next-piece preview, gravity direction control, and 5 visual themes.

```
╔══════════════════════════════════════════════════════════════════════╗
║              ▶ TETRIS·SCAPE — GAME MODE ◀                           ║
╠══════════╦═══════════════════════╦═══════════════════════════════════╣
║  SCORE   ║                       ║  CONTROLS                         ║
║  03200   ║  ░░░░░░░░░░░░░░░░░░░  ║  MOVE                             ║
║  LINES   ║  ░░░░░░░░░░░░░░░░░░░  ║  [←] Move Left                   ║
║  24      ║  ░░░░░░░░░░░░░░░░░░░  ║  [→] Move Right                  ║
║  LEVEL   ║  ░░░░░░░░████░░░░░░░  ║  [↑] Rotate CW                   ║
║  3       ║  ░░░░░░░░████░░░░░░░  ║  [↓] Soft Drop                   ║
║  BEST    ║  ░░░░░░░░░░░░░░░░░░░  ║  ROTATE                           ║
║  08500   ║  ░░░░░░░░░░░░░░░░░░░  ║  [Z] CW  [X] CCW                 ║
║          ║  ░░░░░░████████░░░░░  ║  [Space] Hard Drop               ║
║  NEXT    ║  ░░░░████████░░░░░░░  ║  [P] Pause                       ║
║  ┌─██─┐  ║  ░░░░████████░░░░░░░  ║                                   ║
║  └─██─┘  ║  ░░░░░░░░░░░░░░░░░░░  ║  ACTIONS                          ║
║          ║  ████████████████████  ║  [⏸ PAUSE  P]                    ║
║  GRAVITY ║                       ║  [↺ RESTART]                     ║
║    [↑]   ║                       ║  [✕ EXIT GAME]                   ║
║  [←][↓][→]                       ║  THEME                            ║
║          ║                       ║  ● ○ ○ ○ ○  NEON                 ║
╚══════════╩═══════════════════════╩═══════════════════════════════════╝
```

---

### 🌌 Live Background Mode

> After clicking **▶ Apply as BG**, your block design becomes an animated pixel-art background. The canvas fades in and animates behind all UI elements.

```
╔══════════════════════════════════════════════════════════════════════╗
║  [✦ LIVE BG ACTIVE badge glows in corner]                           ║
║                                                                      ║
║  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·     ║
║  ·  ·  ·  ██████  ·  ·  ·  ·  ·  ·  ·  ██  ·  ·  ·  ·  ·  ·  ·   ║
║  ·  ·  ·  ██████  ·  ·  ·  ·  ·  ·  ████  ·  ·  ·  ·  ·  ·  ·    ║
║  ·  ·  ·  ·  ·  ·  ·  ·  ·  ██████████  ·  ·  ·  ·  ·  ·  ·  ·   ║
║  ·  ·  ████  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ████████  ·  ·  ║
║  ·  ·  ████  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ████████  ·  ·  ║
║  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·     ║
║        ↑ Blocks glow with neon box-shadow & scanline overlay        ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

### 📚 Design Library

> Save, browse, load, rename, pin, duplicate, and delete your designs — with canvas thumbnail previews.

```
╔══════════════════════════════════════════════════════════════════════╗
║  ✦ DESIGN LIBRARY           [SEARCH DESIGNS...]  [Newest ▼]  [✕]   ║
║  Your saved Tetris·Scape creations                                   ║
║  TOTAL: 5   PINNED: 1   TOTAL BLOCKS: 47                            ║
║  [ALL] [★ PINNED] [NEON] [LAVA] [GAMEBOY] [NES]                    ║
╠════════════╦════════════╦════════════╦════════════╦════════════╣
║ ┌────────┐ ║ ┌────────┐ ║ ┌────────┐ ║ ┌────────┐ ║            ║
║ │▓▓░░░░▓▓│ ║ │░░▓▓▓░░░│ ║ │▓░░░░░▓░│ ║ │░░▓▓░░░░│ ║            ║
║ │░░▓▓░░░░│ ║ │░░░░▓▓▓░│ ║ │░▓▓░░░░░│ ║ │▓▓░░░▓▓░│ ║            ║
║ │▓░░░▓▓░░│ ║ │▓░░░░░▓▓│ ║ │░░░▓▓▓░░│ ║ │░░░░▓░░░│ ║            ║
║ └────────┘ ║ └────────┘ ║ └────────┘ ║ └────────┘ ║            ║
║ ★ NEON     ║  LAVA FLOW ║  GAMEBOY   ║  GRID ART  ║            ║
║  WAVES     ║            ║  CLASSIC   ║            ║            ║
║ 2024-01-15 ║ 2024-01-14 ║ 2024-01-12 ║ 2024-01-10 ║            ║
║ NEON  12BLK║ LAVA   9BLK║ GAME  15BLK║ NEON  11BLK║            ║
║ [✎][⊕][✕] ║ [✎][⊕][✕] ║ [✎][⊕][✕] ║ [✎][⊕][✕] ║            ║
╚════════════╩════════════╩════════════╩════════════╩════════════╝
```

---

### ⚙ Settings Panel

> Rename the game, change UI label text, set the title color mode (rainbow or solid), customize UI accent colors with presets, and save designs directly from settings.

```
╔═══════════════════════════════════════════╗
║  ⚙ GAME SETTINGS                    [✕]  ║
╠═══════════════════════════════════════════╣
║  🎮 GAME NAME                             ║
║  [✦ TETRIS·SCAPE ✦_________________]     ║
║                                           ║
║  🎨 NAME COLOR                            ║
║  [🌈 RAINBOW]  [🎨 SOLID]                 ║
║                                           ║
║  ✏ RENAME UI LABELS                       ║
║  — HEADER —                               ║
║  SUBTITLE  [Stack blocks. Build worlds.]  ║
║  GAME MODE [▶ TETRIS·SCAPE — GAME MODE]   ║
║  BG BADGE  [✦ LIVE BG ACTIVE          ]   ║
║  — PANEL TITLES —                         ║
║  PIECES    [» PIECES                  ]   ║
║  CANVAS    [» CANVAS — click to place ]   ║
║                                           ║
║  🎨 UI COLOR THEME                        ║
║  HEADER      ■ [  #00fff0  ] [↺]         ║
║  PANEL TITLE ■ [  #00fff0  ] [↺]         ║
║  SECTION HDR ■ [  #00fff0  ] [↺]         ║
║  BUTTON      ■ [  #00fff0  ] [↺]         ║
║  BTN HOVER   ■ [  #ff00aa  ] [↺]         ║
║  BTN TEXT    ■ [  #e0e0ff  ] [↺]         ║
║  PRESETS: [NEON][MAGENTA][YELLOW][PURPLE] ║
║                                           ║
║  💾 SAVE DESIGN TO LIBRARY               ║
║  [DESIGN NAME...___________________]     ║
║  [💾 SAVE TO MY DESIGNS]                  ║
╠═══════════════════════════════════════════╣
║         [✔ APPLY]    [↺ RESET]           ║
╚═══════════════════════════════════════════╝
```

---

### ✦ Customize Panel  ·  Visual Themes

```
╔════════════════════════════╗    ╔═══════════════════════════════════╗
║  ✦ CUSTOMIZE UI      [✕]  ║    ║  VISUAL THEMES — switch anytime   ║
╠════════════════════════════╣    ╠═══════════════════════════════════╣
║  HEADER BUTTONS SIZE        ║    ║  ● NEON      Cyan glow on black   ║
║  [━━━●━━━━━━━━━━] 9px       ║    ║  ○ 99        Blue arcade cabinet  ║
║                             ║    ║  ○ GAMEBOY   Green monochrome LCD ║
║  HEADER BUTTONS PADDING     ║    ║  ○ LAVA      Hot orange on black  ║
║  TOP/BTM [━●━━━━━━━━] 10px  ║    ║  ○ NES       Grey 8-bit console   ║
║  L/R     [━━●━━━━━━━] 16px  ║    ║                                   ║
║                             ║    ║  Each theme changes:              ║
║  PANEL BUTTONS SIZE         ║    ║  • All CSS color variables        ║
║  [━━━━━●━━━━━━━━] 14px      ║    ║  • Block piece colors             ║
║                             ║    ║  • Board background               ║
║  PANEL BUTTONS PADDING      ║    ║  • Background music pattern       ║
║  [━━●━━━━━━━━━━━] 8px       ║    ║  • Game panel styling             ║
║                             ║    ║                                   ║
║  [✔ APPLY SIZES]            ║    ╚═══════════════════════════════════╝
║  [↺ RESET TO DEFAULT]       ║
╚════════════════════════════╝
```

---

## 🚀 Features

### 🎨 Design Editor
- **8 Tetris piece types** — I, O, T, S, Z, J, L, and a single-cell X piece
- **Full color control** — 8 preset palette swatches, color wheel, hex input, and custom color saving
- **Rotation** — Rotate any placed piece in 90° increments with `R` or the Rotate button
- **Select & edit** — Click any block to select it, then rotate, delete, or recolor
- **Undo / Redo** — Full history with `Ctrl+Z` / `Ctrl+Y` / `Ctrl+Shift+Z`
- **Block placement animations** — Particle burst effect on every placed piece
- **20×22 grid canvas** — Large workspace for complex designs

### 🌌 Live Background Engine
- **Apply as BG** — Renders your design to a canvas and uses it as an animated live background
- **Scanline overlay** — CRT-style scanline effect across the entire page
- **Smooth fade** — 1 second transition when activating/deactivating background
- **Persistent** — Background state is saved and restored automatically

### 🎮 Tetris Game
- **Full Tetris rules** — Piece spawning, line clearing, leveling, and scoring
- **4-directional gravity** — Switch gravity mid-game: down, up, left, or right
- **Ghost piece** — See where pieces will land
- **Hard drop** — Spacebar instant drop with slam animation and screen shake
- **Smooth animations** — Fall, rotate, spawn, line-shatter, and particle effects
- **High score tracking** — Persistent best score with "NEW RECORD" celebration
- **Import game design** — Keep your Tetris board pattern as an editor design

### 🎵 Audio Engine
- **Procedural chiptune music** — All music generated via Web Audio API, no audio files
- **5 music tracks** — NEON, BATTLE, GAMEBOY, LAVA, NES with distinct patterns and BPMs
- **Interactive track lever** — Drag a slider or click tick marks to switch tracks live
- **Rich SFX** — Unique sounds for: piece placement, rotation, hard drop, line clear, level up, game over, gravity change, and UI interactions
- **Music visualizer** — Animated bar graph synced to the beat

### 📚 Design Library
- **Persistent storage** — Saves to `window.storage` (survives sessions)
- **Card thumbnails** — Canvas-rendered preview of every saved design
- **Full management** — Save, load, rename, duplicate, pin, delete
- **Search & filter** — Filter by theme, pin status, or search by name/tag
- **Sort options** — Newest, oldest, name, block count, pinned first
- **Tags** — Label designs with custom tags when saving
- **URL sharing** — Generate a shareable link that encodes your full design in the URL hash

### ⚙ Settings & Customization
- **Game name** — Rename the title with rainbow or solid color modes
- **UI label editor** — Rename every heading, panel title, button label, and badge
- **UI color theme** — 6 independent color pickers for header, panel titles, section headings, buttons, hover state, and button text — with 5 presets (NEON, MAGENTA, YELLOW, GREEN, PURPLE)
- **Button size panel** — Sliders to independently control header and panel button font size and padding
- **5 visual themes** — NEON, 99, GAMEBOY, LAVA, NES — each with full CSS variable overrides, unique block styling, and matching music

### 🔧 Technical
- **Zero dependencies** — Pure HTML + CSS + JavaScript, no frameworks, no libraries, no CDN
- **Single file** — The entire app is one `.html` file, open it locally or host anywhere
- **Export PNG** — Downloads your canvas design as a PNG image
- **URL share** — Full design encoded in the URL hash for instant sharing
- **Auto-save** — Design state is automatically saved before page close
- **Responsive** — Flex layout adapts to different screen sizes

---

## 🗂 Project Structure

```
tetrisscape/
└── index.html          ← The entire application (one file!)
    ├── <style>         ← ~1,600 lines of CSS
    │   ├── CSS custom properties (theme variables)
    │   ├── Game board & piece animations
    │   ├── Design editor layout
    │   ├── Library overlay & cards
    │   ├── Settings & customize modals
    │   └── UI color customization system
    ├── <body>          ← All HTML markup
    │   ├── Header with navigation buttons
    │   ├── Game overlay (Tetris board)
    │   ├── Design editor (3-panel layout)
    │   ├── Library overlay
    │   ├── Settings modal
    │   ├── Customize modal
    │   └── Toast / confirm modals
    └── <script>        ← ~3,000 lines of JavaScript
        ├── Design editor state & rendering
        ├── Undo / redo engine
        ├── Background rendering engine
        ├── Tetris game engine (gravity, physics, scoring)
        ├── Theme engine (5 themes)
        ├── Web Audio engine (procedural chiptune + SFX)
        ├── Music track selector
        ├── Design library engine
        ├── URL share / export engine
        ├── Settings module
        ├── Customize module
        └── UI color customization module
```

---

## ⚡ Getting Started

### Option 1 — Open Directly

```bash
git clone https://github.com/yourusername/tetrisscape.git
cd tetrisscape
# Just open index.html in any browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 2 — Local Server (recommended for storage features)

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .

# Then visit http://localhost:8080
```

### Option 3 — Deploy to GitHub Pages

1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages → Source: Deploy from branch → main / root**
3. Your site will be live at `https://yourusername.github.io/tetrisscape/`

---

## 🕹 Controls Reference

### Design Editor

| Action | Keyboard | Mouse |
|--------|----------|-------|
| Place block | — | Click canvas cell |
| Select block | — | Click placed block |
| Rotate selected | `R` | Click Rotate button |
| Delete selected | `Delete` / `Backspace` | Click Delete Block |
| Deselect | `Escape` | Click empty canvas |
| Undo | `Ctrl+Z` | Click ↩ UNDO |
| Redo | `Ctrl+Y` / `Ctrl+Shift+Z` | Click REDO ↪ |

### Tetris Game

| Action | Key |
|--------|-----|
| Move left/right | `← →` |
| Soft drop | `↓` |
| Rotate CW | `↑` or `Z` |
| Rotate CCW | `X` |
| Hard drop | `Space` |
| Pause / Resume | `P` |

---

## 🎨 Visual Themes

| Theme | Colors | Vibe | Music BPM |
|-------|--------|------|-----------|
| **NEON** | Cyan `#00fff0` + Magenta | Dark cyberpunk | 138 |
| **99** | Blue `#0055aa` + Yellow | Arcade cabinet | 160 |
| **GAMEBOY** | Green `#8bac0f` monochrome | Retro handheld LCD | 120 |
| **LAVA** | Orange-red on black | Underground heat | 148 |
| **NES** | Grey `#3860b0` + white | 8-bit console | 150 |

Each theme overrides all CSS variables, block piece colors, board background, game panel styles, and switches the background music pattern.

---

## 🔊 Audio System

All music and sound effects are **generated entirely in JavaScript** using the Web Audio API — no audio files are loaded. The chiptune engine uses oscillators, envelope shaping, and a custom music pattern system with 4 scales:

- **Major scale** — Upbeat melodies (NEON, NES)
- **Minor scale** — Tense battle feel (BATTLE)
- **Pentatonic** — Classic chiptune (GAMEBOY)
- **Chromatic** — Eerie, volatile (LAVA)

Sound effects include: piece placement, rotation, hard drop whoosh, slam impact, line clear sweep, shatter crackle, particles, score pop chime, level up fanfare, game over crash, gravity change swoosh, pause blip, and UI click.

---

## 🧩 Block Pieces

| Piece | Shape | Default Color |
|-------|-------|---------------|
| **I** | `████` (4-long bar) | Cyan `#00fff0` |
| **O** | `██`/`██` (2×2 square) | Yellow `#ffee00` |
| **T** | T-shape | Purple `#aa44ff` |
| **S** | S-shape | Green `#00ff88` |
| **Z** | Z-shape | Red `#ff4455` |
| **J** | J-shape | Blue `#22aaff` |
| **L** | L-shape | Orange `#ff6622` |
| **X** | Single cell | White `#ffffff` |

All pieces can be rotated in 4 orientations and placed in any custom color.

---

## 💡 Tips & Tricks

- **Use X pieces** as single-pixel accent dots to add detail to large designs
- **Change gravity mid-Tetris-game** — lines clear along the gravity wall, not just horizontally
- **Apply as BG → play Tetris** — your design animates underneath the game board
- **URL share links** encode the full design — bookmark or tweet your creations
- **Color preset YELLOW** sets button text to black automatically for contrast
- **Pin your favorite designs** in the library so they always appear at the top
- **Quick Save / Load** uses localStorage for a fast single-slot save separate from the full library
- **Duplicate** a design before experimenting so you always have a fallback

---

## 🤝 Contributing

Pull requests welcome! Some ideas for contribution:

- [ ] More piece types (pentominoes, custom shapes)
- [ ] Additional visual themes
- [ ] More music patterns / scales
- [ ] Animation modes for the live background (scrolling, pulsing)
- [ ] Touch / mobile drag-to-place support
- [ ] Color palette import from image
- [ ] Design tags and folders in the library

---

## 📄 License

MIT License — do whatever you want with it.

---

<div align="center">

Made with ✦ neon and `Web Audio API` and zero npm installs

**[⭐ Star this repo if you like it!]**

</div>

