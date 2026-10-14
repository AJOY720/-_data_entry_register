DATA ENTRY REGISTER PWA — SETUP GUIDE

FILES
- index.html: your data-entry app
- manifest.json: installable-app metadata
- sw.js: offline cache/service worker
- icons/: app icons

PUBLISH WITH GITHUB PAGES
1. Sign in to GitHub and create a public repository named data-entry-register.
2. Upload all files from this ZIP. index.html, manifest.json and sw.js must be in the repository root; keep the icons folder.
3. Open Settings > Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for the Pages URL, typically https://YOUR-USERNAME.github.io/data-entry-register/
7. Open the HTTPS URL in Chrome on Android. Tap ⋮ > Add to Home screen or Install app.

IMPORTANT
Records are stored locally in the browser on this device. Export CSV and use Backup Data regularly. This app does not sync between devices and does not use an online database.
