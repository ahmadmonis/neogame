# NEON RUN

3D endless highway racing game built with Three.js (single `index.html`, no build step).

**Controls:** A/D or arrow keys to change lanes, Space for nitro, S/Down to brake, Esc/P to pause, M to mute. Touch: swipe or use the on-screen buttons.

## Run locally
Open `index.html` in a browser (needs internet for the Three.js CDN).

## Deploy with GitHub Pages
Repo **Settings → Pages → Deploy from a branch → `main` / root**.

## AdSense (optional)
Edit the `ADS` constant near the top of the script in `index.html`:
```js
const ADS={client:'ca-pub-XXXXXXXXXXXXXXXX', slot:'1234567890', test:true, ok:true};
```
Set `test:false` before going live. Ads show only on menu, pause and game-over screens.
