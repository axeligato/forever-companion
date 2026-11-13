# Forever Companion

A mobile-first, unofficial WoW Forever companion PWA.

## Features
- Editable character profile (class, spec, level, profession and skill)
- Session goals and checklist
- Gear wishlist and acquisition tracking
- Profession recipe browser with clearly labeled fictional demo entries
- Offline-friendly service worker and installable PWA manifest
- Local browser storage and JSON export

## Deploy on Vercel
Import this GitHub repository at https://vercel.com/new. Select **Other** framework preset, leave build command blank, and use the repository root as output directory (static site). Deploy. Subsequent commits to main redeploy automatically.

## Run locally
Open `index.html` in a browser for a quick preview. For PWA/service-worker testing, use a local static server (e.g. `python3 -m http.server 8000`) and visit http://localhost:8000.

## Important
Recipes in v1 are fictional examples, **not verified WoW Forever game data**. No Blizzard or server affiliation is claimed. User progress is saved locally per browser/device; clearing site data removes it. Export a backup from Goals.
