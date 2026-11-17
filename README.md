# Batik Mega Mendung

A custom skin for the Video.js 10 player, built for the Contra x Mux Video.js Skins Design Challenge.

The timeline is a mega mendung cloud wave that fills with gold as the story moves. The play button is a gold ring medallion, and the control bar is deep indigo with a faint batik cloud pattern.

## Try it

Open `index.html` after building, or visit the live demo linked in the challenge post.

## Build

```bash
npm install
npm run build
```

This bundles `src/main.js` (Video.js 10 web components plus the skin) into `bundle.js` and `bundle.css` with esbuild.

## What is inside

- `index.html`, the demo page with the player markup
- `src/main.js`, the component imports
- `src/skin.css`, the whole skin: wave timeline, medallion play button, indigo control bar, gold controls

## Controls

Play and pause, seek on the wave timeline, volume, playback speed, fullscreen, plus keyboard shortcuts (Space, M, F, Left, Right) and click and double-click gestures on the video.

Demo video: the Mux sample asset used in the Video.js docs.

By Muhamad Fahrurrozi, 2026. MIT licensed.
