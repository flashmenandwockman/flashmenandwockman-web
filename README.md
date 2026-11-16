# flashmen-wockman.com

Static website of FLASHMEN AND WOCKMAN. No build step: plain HTML, CSS and JS.

## Files
- `index.html` – landing page
- `projects.html` – current projects (Cardisio, Pacture, Investment Arena)
- `styles.css`, `site.js` – shared design system and behaviour
- `bilder/` – logos and images
- `netlify.toml` – headers and redirects for Netlify

## Deploy (Netlify, recommended)
1. Push this folder to GitHub (`main` branch).
2. Netlify → "Add new site" → "Import an existing project" → pick the repo.
3. Build command: leave empty. Publish directory: `.`
4. Domain settings → add `flashmen-wockman.com` and `www.flashmen-wockman.com`, then point the DNS at Netlify (A record `75.2.60.5` or Netlify DNS). HTTPS is issued automatically.

Every push to `main` deploys automatically.

## Deploy (GitHub Pages, alternative)
Settings → Pages → Source "Deploy from a branch" → `main` / root. Add a `CNAME` file containing `flashmen-wockman.com` and point the DNS A records to GitHub Pages.
