# Pixel Manhattan

A generative, side-scrolling pixel-art Manhattan street world. Every visit
is a different city: a fresh seed picks the buildings — brownstones with
stoops, tenements with fire escapes, painted East Village walk-ups, shops
with awnings, prewar towers with water tanks — and one of five times of
day, then fills the street with people who stroll, chat, walk dogs and sit
on the stoops. Drag to look around; tap the arrow to generate a new city.

Everything lives in a single dependency-free `index.html`.

## Running it

Open `index.html` in a browser, or serve the folder from any static host.

## Installing as an app (PWA)

The repo ships a web-app manifest (`manifest.webmanifest`), icons, and an
offline-caching service worker (`sw.js`). Served over HTTPS — for example
with GitHub Pages — it becomes installable:

1. Enable Pages: **Settings → Pages → Deploy from a branch**, pick the
   branch and `/ (root)`.
2. Open the Pages URL on your phone.
3. **Add to Home Screen** (iOS Safari share menu, or Android Chrome's
   install prompt). It launches fullscreen and keeps working offline.
