# George Sertaridis — CV / Portfolio

Dark, premium single-page CV / portfolio. Built with Tailwind (CDN), vanilla JS, and Lucide icons. Fully self-contained and GitHub-Pages ready.

## Deploy (GitHub Pages)
1. Copy the contents of this folder (`index.html` + `assets/`) to the **root** of your `develop` (or `main`) branch.
2. Push, then enable **Settings → Pages → Deploy from branch** and pick the branch + `/ (root)`.

```bash
git checkout -b develop
git add .
git commit -m "v1: dark bento CV/portfolio + animated DevOps pipeline"
git push -u origin develop
```

## Files
- `index.html` — the full site (hero, client logos, experience timeline, bento showcase, animated DevOps pipeline, skills, contact).
- `assets/logos/cropped/` — Accenture, Eurobank, Piraeus, Deutsche Telekom marks.
- `assets/George_Sertaridis_CV.pdf` — downloadable CV (wired to the “Download CV” buttons).

## Notes
- Fonts (Geist / Geist Mono) and icons (Lucide) load from CDN — needs internet on first load.
- The DevOps pipeline supports Row / Cycle / ∞-Loop shapes; the default is Row. To ship ∞-Loop as default, set `"layout": "infinity"` in the `DEFAULTS` block inside `index.html`.
