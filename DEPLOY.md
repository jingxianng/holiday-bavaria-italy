# Deploying the trip sites

The site is fully static: a landing page at `site/index.html` plus one self-contained folder per trip under `site/<trip-slug>/`. No build step, no dependencies.

## Preview locally

Open `site/index.html` (or any `site/<trip-slug>/index.html`) in a browser. From WSL:

```bash
explorer.exe "$(wslpath -w site/index.html)"
```

## GitHub Pages

Already set up for this repo (`jingxianng/holiday-presentation`): Settings → Pages → Deploy from branch → `main`, folder `/ (root)`. Pushing to `main` publishes automatically.

- Landing page: `https://<user>.github.io/holiday-presentation/site/`
- A trip: `https://<user>.github.io/holiday-presentation/site/<trip-slug>/`

Share the trip URL directly with family — the landing page is just a convenient hub.

Every page carries `<meta name="robots" content="noindex">` so the site stays out of search engines even when public. Keep that tag in new trip pages.

## Personal domain

Upload the contents of `site/` (the landing `index.html` plus each trip folder) to any static host or web root. Trip pages use only relative paths, so a single trip folder can also be hosted standalone.

## Adding a new trip

See [README.md](README.md#adding-a-new-trip).
