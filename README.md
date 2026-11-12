# BMW CITY RACING

A free, static browser-based 3D city driving game. No backend or paid service is required to run the site.

## Run locally
Open `index.html` in a modern browser with an internet connection. For best results, use a local static server:
- VS Code: install Live Server, then open `index.html` with Live Server.
- Or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

The game loads Three.js and the vehicle GLB model from public CDNs, so internet access is required.

## Free public hosting (Cloudflare Pages)
1. Create a free GitHub account and a new public repository named `bmw-city-racing`.
2. Upload `index.html` and this `README.md` to the repository root.
3. In Cloudflare, open Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository. Use no build command and set the output directory to `/` (root).
5. Deploy. Cloudflare gives you a public `*.pages.dev` URL that anyone can open.
6. Add the site in Google Search Console and request indexing. Google indexing/ranking is not instant or guaranteed.

## Controls
- W / Up Arrow: accelerate
- S / Down Arrow: brake
- A / D or Left / Right: steer
- Space: nitro
- P: pause
- Touch controls are available on mobile.

## 3D model attribution
“BMW M4 Competition M Package” by **SRT Performance** — Sketchfab.
Source: https://sketchfab.com/3d-models/bmw-m4-competition-m-package-5c0a2dafb1ad408d9fc9eeef9aee531b
License: **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
License: https://creativecommons.org/licenses/by/4.0/
The game uses a web-optimized derivative hosted in the public repository `lukaizj/car-mod-saas`; attribution is retained in the GLB metadata and credited here.

This is an unofficial fan-made project and is not affiliated with, sponsored by, or endorsed by BMW AG. BMW and M4 are trademarks of their respective owners.
