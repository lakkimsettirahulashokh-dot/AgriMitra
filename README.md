# AgriMitra — Smarter Farming Starts Here

A responsive, browser-only farming companion prototype with a seed quantity estimator, local field journal and general crop-planning guidance.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. No installation, API key, server, or database is required.

## Features
- Responsive farmer-friendly landing page
- Seed quantity estimator using user-entered field area and seed rate
- Field journal saved locally in the current browser
- General soil, weather and farm-input guidance
- Mobile navigation

## Important limitations
AgriMitra does not fetch live weather, soil, land-record or market data. It does not diagnose soil conditions or prescribe fertilizer quantities. The calculator only multiplies the values entered by the user. Always use soil-test results and crop-specific recommendations from a qualified local agriculture extension officer or recognized agricultural institution before making farm-input decisions. Field notes stay in local browser storage and are not synced.

## Project structure
- `index.html` — page structure
- `styles.css` — responsive visual design
- `app.js` — calculator, notes and interactions
