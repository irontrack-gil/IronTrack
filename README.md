# IronTrack

Personal workout, nutrition, progress and daily-goal tracker.

## v11
- Improved PWA/service-worker update handling.
- Checks for a newer service worker on app load.
- Uses `updateViaCache: "none"` for faster update detection.
- New service workers activate immediately with `skipWaiting()` and `clients.claim()`.
- Navigations prefer the newest network version, with offline cache fallback.
- Existing IronTrack data in localStorage is preserved during updates.

For GitHub Pages, keep these files at the repository root, including `index.html`.
