# TechQuest: IT Adventure — GitHub Pages

This folder is prepared to publish directly from the root of a GitHub repository.

## Repository layout

- `index.html` — main game page
- `manifest.webmanifest` — PWA metadata
- `register-sw.js` — service-worker registration
- `sw.js` — offline caching
- `.nojekyll` — prevents Jekyll processing
- `assets/` — game art and zone backgrounds

## GitHub Pages

1. Create a repository, for example `techquest`.
2. Upload **the contents of this folder**, not the `ghpages` folder itself.
3. Make sure `index.html` is in the repository root.
4. In GitHub, open **Settings → Pages**.
5. Choose **Deploy from a branch**.
6. Select your main branch and the `/ (root)` folder.
7. Save and wait for the Pages deployment.

The resulting address will normally be:

`https://YOUR-USERNAME.github.io/techquest/`

## Important

Keep the `assets` folder beside `index.html`. Do not move `index.html` into another folder or the game will lose its relative asset paths.
