# BTC WIDE LED WALL — team site

One static page. No build step.

## Deploy to Vercel

**Option A — drag and drop**
1. Go to https://vercel.com/new
2. Drag this folder onto the page (or zip it and upload)
3. Framework preset: **Other**. Leave build command and output directory empty
4. Deploy

**Option B — Git**
1. Push this folder to a GitHub repo
2. Import the repo at https://vercel.com/new, preset **Other**, deploy

**Option C — CLI**
```
npm i -g vercel
vercel --prod
```

## Before you deploy
Search `index.html` for these placeholders and fill them in:
- `{BUTTON NAME}` × 3 — which LED SETTING key fires the A+A, slide+camera and A+B scenes (WINDOWS WIRELESS and PP7 WIDE SCREEN are already filled in)
- `{CONTACT EMAIL}` — where the "Send your pick" link should go

## Files
- `index.html` — the whole site (CSS, JS and the test-pattern PNG are inline)
- `vercel.json` — clean URLs and two security headers; optional
