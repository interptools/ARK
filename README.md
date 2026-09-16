# ARK Apparel  — POS

Built with the Arroyo POS Engine. These files are a complete installable web app.

## Put it online (GitHub Pages, free)

1. Create a new **public** repository on GitHub.
2. Upload **everything in this folder**, keeping the `icons/` folder intact:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `.nojekyll`
   - `icons/` (4 PNG files)
3. **Settings → Pages →** Branch `main`, folder `/ (root)` → **Save**.
4. Wait ~1 minute, then open `https://<username>.github.io/ark-apparel/`

## Install on a phone

- **Android / Chrome:** menu → *Install app*
- **iPhone / Safari:** Share → *Add to Home Screen*

It then opens full screen with its own icon and works without a signal.

## Updating

Regenerate in the builder and replace `index.html` and `sw.js`. Every build gets a
fresh cache name, so devices load the new version on the next open. Sales, stock and
settings already saved on a device are not touched.

## Notes

- All data lives in the browser on each device. Two phones do not share data.
- Use the Sales tab **CSV** button to get data out for backup or accounting.
- Clearing the browser storage for the site erases its records, so export regularly.
