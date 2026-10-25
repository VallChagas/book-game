# The Master Bookbinder & The Lost Manuscripts

A web-based manuscript restoration game where players clean, bind, and enchant ancient tomes for legendary patrons.
> **Live**: https://vallchagas.github.io/book-game/

## Table of Contents

- #background
- #install
- #usage
- #gameplay
- #technologies
- #deployment
- #maintainers
- #thanks
- #contributing
- #license

## Background

This project was built during the **Agentic Deployment Workshop: Ship Your AI Web-App to the World with GitHub**, co-hosted by Women Techmakers Hong Kong and Singapore's AI community Electric Minds. The workshop explored "Vibe-Coding" using AI to generate code and then shipping it live using GitHub Pages' free static hosting.

The game itself is a love letter to the craft of bookbinding. Players take on the role of a Master Bookbinder restoring magical grimoires and lost manuscripts for clients including wizards, alchemists, time travelers, and scholars.

It is a single-file HTML application with zero external dependencies beyond CDN-hosted Tailwind CSS and Google Fonts.

## Install

This is a static web project with no build step or dependencies to install. Simply clone the repository and open the file in a browser.

```bash
git clone https://github.com/VallChagas/book-game.git
cd your-repo
```

## Usage

Open `index.html` directly in any modern web browser:

```bash
open index.html
```

Or serve it locally with any static file server:

```bash
npx serve .
```

## Gameplay

The workbench is divided into three restoration stages per manuscript:

1. **Cleaning & Alignment**  
   Scrub ink blotches from the parchment with a sponge brush and stitch torn pages by clicking the holes along the tear line.

2. **Leather Binding**  
   Choose a leather cover (Dragon Calfskin, Enchanted Velvet, or Obsidian Hide), emboss a foil emblem, and select corner clasps in a live cover preview.

3. **Rune Inscription**  
   Trace the glowing rune nodes to seal the tome's magic and unlock its translated lore.

Completing a commission earns **Gold** and **XP**, with rank progression from *Apprentice Bookbinder* to *Grand Archivist*.

Purchasable upgrades include:

- **Bone Folder** (faster ink scrubbing)
- **Gold Leaf Brush** (+25% gold reward)

Restored manuscripts are added to the **Codex**, where their stories can be read in a parchment-styled reader modal.

## Technologies

- **HTML5** and **Tailwind CSS** (via CDN)
- **Vanilla JavaScript** with no frameworks or bundlers
- **Canvas API** for the ink-scrubbing, stitching, and rune-tracing mini-games
- **Web Audio API** for synthesized sound effects (scrubbing, stitching, chimes) without external audio files
- **Google Fonts**:
  - Cinzel
  - IM Fell English
  - Plus Jakarta Sans

## Deployment

The project is deployed for free via **GitHub Pages**:

1. Push the repository to GitHub.
2. Navigate to **Settings → Pages**.
3. Set the source branch to `main` (or `master`) and the folder to `/root`.
4. Save. The game will be live at:

```text
https://vallchagas.github.io/book-game/
```

## Maintainers

This project is currently maintained by the workshop participant who built it.

Contact via GitHub Issues on the repository.

## Thanks

- **Women Techmakers Hong Kong** and **Electric Minds (Singapore)** for organizing the workshop.
- **Judy Wong** for the inspiring session on unconventional vibe-coding use cases.
- The open-source community behind Tailwind CSS, Google Fonts, and GitHub Pages.

## Contributing

Questions and feedback are welcome via GitHub Issues:

<https://https://github.com/VallChagas/book-game/issues>

Pull requests are accepted for:

- Bug fixes
- Accessibility improvements
- Additional manuscripts in the `BOOKS_DATABASE` array

Please open an issue first to discuss larger changes.

Be kind and constructive in all interactions.

## License

MIT © 2026 — The Master Bookbinder & The Lost Manuscripts contributors.
