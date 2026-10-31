REPLOG V2 – iPhone PWA

INSTALLATION:
1. Host this folder on an HTTPS static host (for example GitHub Pages, Netlify, or a private web host).
2. Open the HTTPS URL in Safari on your iPhone.
3. Tap Share > Add to Home Screen.
4. Launch REPLOG from the Home Screen.

DATA:
- Workout data is stored locally in IndexedDB in the browser on this device.
- Use Export > JSON regularly to create a backup.
- CSV export contains completed set records.
- Import JSON restores a previous backup.

NOTE:
This is a client-side PWA prototype, not an App Store native app.
Service worker/offline installation requires HTTPS or localhost.
