# Step Tracker

A lightweight, no-install step tracker that runs entirely in your browser — no accounts, no backend, no data ever leaves your device.

Open `index.html` in a browser (or visit the app's published URL) to use it.

## Features

- Daily step ring with a customizable goal, plus age-based healthy-goal guidance
- Motion-sensor step counting (with a two-phase calibration flow to tune accuracy to your device) or manual logging
- Import step history from an Apple Health export or a generic CSV (Fitbit, Google Fit, Garmin, etc.)
- 7-day history chart with calorie and distance estimates
- Light / dark / system theme
- Invite friends via the Web Share API or a copyable link
- All data is stored locally in your browser (`localStorage`) — nothing is uploaded anywhere

## Tech

Single self-contained HTML file — vanilla JS, no build step, no dependencies beyond a CDN-loaded JSZip (used only for parsing Apple Health `.zip` exports).
