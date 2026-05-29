# Beyond Gamification — Marketing Site

One-page static site for Beyond Gamification LLC (Ryan Seymour's consulting practice).

## Stack
- Single `index.html` — HTML + embedded CSS, zero build step, zero dependencies.
- Google Fonts (Poppins) loaded via CDN; everything else is system fonts.

## Local preview
Just open the file:
```
open index.html
```
Or run a tiny local server:
```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (Vercel)
This is a static site, so Vercel serves `index.html` with no configuration.

1. Push this folder to a GitHub repo.
2. At vercel.com → "Add New Project" → import the repo.
3. Framework preset: **Other** (no build command, output dir = root).
4. Deploy. You get a `*.vercel.app` URL instantly.
5. (Optional) Add a custom domain (e.g. beyondgamification.com) under Project → Settings → Domains.

## Editing
All content + styling live in `index.html`. Sections are commented (`<!-- HERO -->`, `<!-- WHAT I DO -->`, etc.). Edit, commit, push — Vercel auto-redeploys on every push to the main branch.

## Notes
- Copy is NDA-safe (no internal Amplify product names or metrics).
- Contact CTA points to ry.seymour@gmail.com and the LinkedIn profile.
