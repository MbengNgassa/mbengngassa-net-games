# mbengngassa.net — Games Section & Portfolio Update Pack

Static HTML pages and assets matching `https://mbengngassa.net` (`cinematic.css` / `portfolio-projects.css`), adding a dedicated **Games** arcade section and linking all playable browser games into the portfolio.

## What’s Included (`public_html/`)

### New Pages
- `games.html` — Main **Games Arcade** showcase linking every game
- `pitch-legends-3d.html` — Project page + launch CTA for **Pitch Legends 3D** (`https://mbengngassa.github.io/pitch-legends-3d/`)
- `brickforge-drive.html` — Project page + launch CTA for **BrickForge Drive** (`https://mbengngassa.github.io/brickforge-drive/`)
- `boat-racing.html` — Project page for **Boat Racing** (wired to `/games/boat-racing/` or ready for its live URL)

### Updated Portfolio Pages
- `index.html` — Adds `Games` to header/footer navigation, a **Playable games** 3-card showcase section below Selected Work, and `Games & playable worlds` under *One practice. Many ways of making.*
- `work.html` — Adds `Games arcade ↗` to the archive bar and cards for **Pitch Legends 3D**, **BrickForge Drive**, **Boat Racing**, and **Games Arcade** in *More from the practice*
- `software.html` — Adds `Games` nav + cards for **Pitch Legends 3D**, **BrickForge Drive**, and **Boat Racing** alongside **Pass Pass**, **Soko Soko**, **Tchkap Live AI**, and **Namaste Lover**
- `mind-map.html` — Adds `pitch-legends`, `brickforge`, and `boat-racing` nodes + JSON metadata inside the `Software & games` lane (works natively with `portfolio-map.js`)

### Game Assets (`assets/games/`)
- `pitch-legends-3d.webp` & `pitch-legends-3d-menu.webp`
- `brickforge-drive.webp` & `brickforge-drive-race.webp`
- `boat-racing-preview.svg`

*(Existing site files such as `cinematic.css`, `portfolio-projects.css`, `assets/mark.png`, and `assets/software/tchkap-pop-pose-1.webp` already live on `mbengngassa.net` and are referenced directly so nothing breaks.)*

---

## Option 1: Upload via Hostinger File Manager (1 minute)
1. Download or clone this repository.
2. Open **Hostinger hPanel → Files → File Manager → `public_html/`**.
3. Upload the contents of `public_html/` into `public_html/` on Hostinger (confirming overwrite on `index.html`, `work.html`, `software.html`, and `mind-map.html`, and merging `assets/games/` into `public_html/assets/games/`).
4. Optional for **Boat Racing**:
   - Either upload your Boat Racing HTML/build into `public_html/games/boat-racing/index.html`, **or**
   - Replace `/games/boat-racing/` in `boat-racing.html` with your hosted Boat Racing URL.

## Option 2: Deploy with Hostinger MCP
If you run an AI assistant connected to your **Hostinger MCP** server locally, paste this prompt:

> Deploy all files from `public_html/` in `https://github.com/MbengNgassa/mbengngassa-net-games` into `public_html/` for `mbengngassa.net`, keeping existing `assets/`, CSS, and other `.html` pages intact.
