# SnapMark landing page

The marketing site for SnapMark, the Windows screen capture app. Plain HTML, CSS and JavaScript, so there's no build step.

- `index.html`: page content
- `styles.css`: styles (same violet → cyan theme as the app)
- `script.js`: scroll fade-in
- `assets/img/`: images rendered from the app

Download buttons point to the latest installer in the public
[SnapMark-releases](https://github.com/kamrancreation/SnapMark-releases/releases/latest) repo, so they stay current after every release.

## Going live

The site is hosted with GitHub Pages from the `gh-pages` branch of the public
[SnapMark-releases](https://github.com/kamrancreation/SnapMark-releases) repo:
**https://kamrancreation.github.io/SnapMark-releases/**. This repo stays private.
After committing changes here, publish them with:

```bash
git push https://github.com/kamrancreation/SnapMark-releases.git main:gh-pages
```

## Preview locally

Serve the folder with any static file server, for example:

```bash
npx serve .
```
