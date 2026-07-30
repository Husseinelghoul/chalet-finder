# Chalet Finder 🏡

A single-page web app to browse and compare August 2026 chalet rentals in Lebanon —
availability calendars, pricing, photo galleries, capacity, and amenities across
multiple providers.

## What it is

A self-contained static site: everything lives in **`index.html`** (HTML, CSS and JS),
with local photos under `Chalet_Photos/` and `provider_photos/`. No build step, no
backend.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on **Cloudflare Pages** (static asset hosting). Any push to the `main` branch /
new upload publishes the site.
