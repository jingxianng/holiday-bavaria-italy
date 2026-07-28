# Deploying the trip site

The site is fully static: `site/index.html` + `site/images/` (35 photos, ~8.5 MB total, lazy-loaded). No build step, no dependencies.

## Preview locally

Open `site/index.html` in any browser. From WSL:

```bash
explorer.exe "$(wslpath -w site/index.html)"
```

## GitHub Pages (recommended)

1. Create a repo (public, or private on a paid plan — Pages on private repos requires Pro):
   ```bash
   git init && git add site DEPLOY.md references && git commit -m "Trip site"
   gh repo create holiday-bavaria-italy --private --source . --push
   ```
2. In the repo: Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.
   The site will be at `https://<user>.github.io/holiday-bavaria-italy/site/`.
   - To serve at the repo root instead, move `index.html` and `images/` to the repo root (adjust nothing else — image paths are relative).
3. Optional: add a custom domain under Settings → Pages.

The page carries `<meta name="robots" content="noindex">` so it stays out of search engines even when public.

## Personal domain

Upload `index.html` and the `images/` folder (keeping them side by side) to any static host or web root. Nothing else needed.
