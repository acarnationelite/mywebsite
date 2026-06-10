# MyWebsite

Simple static marketing website containing pages: `index.html`, `about.html`, `services.html`, `contact.html`, `carsales.html` and supporting assets in `assets/`.

## Local preview
- Open `index.html` in a browser: double-click the file or run a simple static server, e.g.:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Notes
- All site assets live under `assets/` (CSS, JS, images, fonts).
- Several links use `javascript:void(0)` as placeholders.

## Deployment suggestions
- Host as a static site: GitHub Pages, Netlify, Vercel, or any static hosting.
- For GitHub Pages, enable Pages for the `master` branch (or `gh-pages` branch) and set the root folder.

If you'd like, I can add a GitHub Actions workflow to run HTML/CSS checks and a simple `check-links` step. What CI provider or checks do you prefer?