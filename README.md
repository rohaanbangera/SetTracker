# SetTracker

A lightweight gym workout tracker that runs in the browser — no backend, no account required.

## Features

- Track exercises, sets, reps, and weight per session
- Each set can have its own reps and weight
- Workout history saved locally in the browser
- Works on mobile

## Usage

Open `index.html` in any browser, or serve it locally:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your browser, or `http://<your-local-ip>:8080` on your phone (must be on the same WiFi).

## Data Storage

All data is stored in `localStorage` — nothing leaves your device.
