# SnapMark landing page

The marketing site for SnapMark, the Windows screen capture app. Plain HTML, CSS and JavaScript, so there's no build step.

- `index.html`: page content
- `styles.css`: styles (same violet → cyan theme as the app)
- `script.js`: scroll fade-in
- `assets/img/`: images rendered from the app

Download buttons point to the latest installer in the public
[SnapMark-releases](https://github.com/kamrancreation/SnapMark-releases/releases/latest) repo, so they stay current after every release.

## Going live

**Vercel (main site):** https://snapmark-omega.vercel.app, from the Vercel project `snapmark`. After committing changes here, publish with:

```bash
vercel deploy --prod
```

**GitHub Pages (backup copy):** https://kamrancreation.github.io/SnapMark-releases/, served from the `gh-pages` branch of the public
[SnapMark-releases](https://github.com/kamrancreation/SnapMark-releases) repo. Update it with:

```bash
git push https://github.com/kamrancreation/SnapMark-releases.git main:gh-pages
```

This repo stays private either way.

## Preview locally

Serve the folder with any static file server, for example:

```bash
npx serve .
```
