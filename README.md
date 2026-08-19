# kurotsuki.dev

Personal site for **Kurotsuki**, hosted via GitHub Pages at [vaporeonscripts.github.io](https://vaporeonscripts.github.io).

Single self-contained `index.html` — no build step, no dependencies beyond Google Fonts.

## What's on it

- **Hero** — fish shell terminal intro
- **Advancements** — project showcase styled after the custom Lucid Advancements theme built for NeoTech Reborn (task / goal / challenge tiers):
  - [NeoTech Reborn](https://www.curseforge.com/minecraft/modpacks/neotech-reborn) — a magic-and-exploration-heavy NeoForge 1.21.1 modpack with deep systems to sink into: 400+ custom enchantments, reworked combat, and 15+ custom dimensions to explore. Live download count pulled from [way2muchnoise](https://www.curseforge.com/minecraft/modpacks/neotech-reborn).
  - [Pack Commit](https://github.com/VaporeonScripts/pack-commit) — a ~1,300-line fish shell tool for modpack sync and git, vibe coded with Claude
  - Italian translation work on *The Coffin of Andy and Leyley*
- **My Setup** — hardware/OS specs plus a small desktop rice showcase
- **Favorite Game** — a dedicated banner section for *The Coffin of Andy and Leyley*
- **About** — short bio
- **Floating music player** — click-to-enter gate, volume control, autoplay-safe

## Structure

```
.
├── index.html        # the whole site
├── assets/
│   ├── wallpaper.png  # desktop screenshot
│   ├── fastfetch.png  # system info screenshot
│   ├── cachyos.png     # CachyOS logo
│   ├── tcoaal.png       # The Coffin of Andy and Leyley cover art
│   ├── server_logo.png # Hall of Modding Discord server icon
│   ├── cover.png       # music player cover art
│   └── theme.mp3        # music player track
└── README.md
```

## Editing

Everything lives in `index.html` — styles, markup, and script are all inline. To change content, find the relevant section by its `id` (`#advancements`, `#setup`, `#favorite-game`, `#about`, `#contact`) and edit directly.

## Deploying

Pushes to `main` are served automatically at `https://vaporeonscripts.github.io` via GitHub Pages — no Actions workflow required.
