# Daily Practice PWA

A small, responsive home-screen web app that links to yoga, meditation and talk resources.

## Files
- `index.html` — page content and service-worker registration
- `styles.css` — responsive dark theme
- `manifest.json` — install metadata
- `sw.js` — offline cache for the app shell
- `icon-180.png`, `icon-192.png`, `icon-512.png` — app icons

## Publish with GitHub Pages (iPhone-friendly route)
1. Create a new repository on GitHub and choose a name such as `daily-practice`.
2. Upload all seven files from this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS URL in Safari on the iPhone.
6. In Safari, tap **Share → Add to Home Screen**. If shown, enable **Open as Web App**, then tap **Add**.

## Notes
- The app shell can load offline after its first successful visit. The external provider websites require an internet connection.
- The Google Fonts import is optional and may not load offline; system fonts are used as fallbacks.
- External links open in a new browser tab/window, which may leave the installed web app.
- GitHub Pages must serve the files over HTTPS for service workers to work.
