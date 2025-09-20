# Scenic Roots Quoter (PWA)

Installable, offline-first quoting app for Scenic Roots. Ready for **GitHub Pages**.

## Deploy on GitHub Pages
1. Create a repo named **scenic-roots-quoter** on your GitHub account.
2. Upload the files from this ZIP (drag/drop in the web UI).
3. Go to **Settings → Pages**.
   - Build and deployment: **Deploy from a branch**
   - Branch: `main` and folder `/ (root)` → **Save**
4. Your site will be at: `https://<your-username>.github.io/scenic-roots-quoter/`
5. Open on your phone and **Add to Home Screen** to install.

## Files
- `index.html` — app with manifest + service worker
- `manifest.json` — install metadata
- `sw.js` — offline cache
- `icon-192.png`, `icon-512.png` — replace with your logo

## Notes
- Quotes you save stay on the device (browser storage).
- After first load, it works offline.
