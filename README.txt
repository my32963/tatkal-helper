# Tatkal Helper PWA

## Files
- `index.html`: Tatkal Helper application
- `manifest.webmanifest`: installable app metadata
- `sw.js`: offline app-shell cache
- `icons/`: app icons

## Run locally
A service worker and PWA installation require a secure context. `https://` hosting is recommended. `http://localhost` is also suitable for local development. Opening `index.html` directly with `file://` will not enable PWA installation or offline caching.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `tatkal-helper`.
2. Upload all files and the `icons` folder, preserving the folder structure.
3. In the repository, open Settings -> Pages.
4. Select deployment from the `main` branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site over HTTPS.
6. Open the published HTTPS URL in Chrome on Android.

## Install on Android
1. Open the published URL in Chrome.
2. Wait for the page to load.
3. If the `Install app` button appears, tap it and confirm.
4. If it does not appear, use Chrome's three-dot menu -> Install app or Add to Home screen (wording varies).

## Important
- Offline mode caches the app shell. IRCTC itself still needs an internet connection.
- Browser reminders are best-effort. They are not guaranteed when the browser is closed, the device sleeps, or Android restricts background activity.
- This is an independent preparation tool, not an IRCTC booking client.
- Do not save passwords, OTPs, full Aadhaar numbers, or payment credentials in the notes.
