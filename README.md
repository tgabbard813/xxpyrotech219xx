# xXpyrotech219Xx — Landing Page (GitHub Pages)

Static site, no build step. Just upload these files.

## Deploy to GitHub Pages

1. Create a new public repo on GitHub (e.g. `pyrotech219-site`).
2. Upload **all files in this folder** (`index.html`, `logo.png`, `.nojekyll`, `404.html`) to the root of the repo.
3. Repo → **Settings → Pages**.
4. Source: **Deploy from a branch**. Branch: **main** / folder: **/ (root)**. Save.
5. Wait ~1 minute, then visit `https://<your-username>.github.io/<repo-name>/`.

## Custom domain (optional)
If you want it on `xxpyrotech219xx.com`, add a `CNAME` file containing just your domain, then point your DNS at GitHub Pages.

## Files
- `index.html` — the whole site
- `logo.png` — your mascot logo
- `.nojekyll` — tells GitHub Pages not to run Jekyll
- `404.html` — fallback page
