# world-travel-tracker

A single-page web app for tracking the countries you've visited.

- A world map that starts white with black borders.
- Below it, all 197 countries listed alphabetically under letter headings, each with a checkbox.
- Tick a country (or tap it on the map) and it's filled in on the map.
- Running total, per-continent progress, search, a "visited only" filter, and zoom/pan on the map.
- Very small countries (Monaco, Malta, Caribbean and Pacific islands) are shown as dots.

## Running it

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → deploy from the `main` branch) to get a live link.

When opened outside Claude, your ticks are saved in your browser's local storage, so they stay on that browser and device.

Map outlines come from [jsVectorMap](https://github.com/themustafaomar/jsvectormap) and load from a CDN, so the page needs an internet connection.
