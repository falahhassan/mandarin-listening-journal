# Mandarin Listening Journal PWA

## Files
- `index.html` — the journal website
- `manifest.webmanifest` — app name, icon, and standalone display settings
- `service-worker.js` — caches the app shell for offline loading
- `icons/` — install icons

## Publish with GitHub Pages
1. Create a new GitHub repository. For personal use, choose **Private** if you have GitHub Pro or another plan that supports Pages on private repositories; otherwise, a public repository means the website files are public.
2. Upload the files and folders from this package to the repository root (not the ZIP file itself).
3. In repository Settings → Pages, choose deployment from the `main` branch and `/ (root)`, then save.
4. Wait for the published HTTPS URL.
5. Open the URL in Chrome on Android, let it load once while online, then use Chrome menu → **Install app** or **Add to Home screen**.

## Privacy note
The website files contain no account or backend. Journal entries are stored in the browser's local storage on the device. Anyone who can open the website URL can use their own local journal; they cannot see your locally stored entries just by visiting the same URL. If you choose a public repository, the HTML and app code are public. GitHub Pages privacy and repository visibility depend on your GitHub plan and settings.

## Back up
Use the app's Export & Backup tab to download the full JSON backup regularly. Local browser data does not automatically sync across devices.
