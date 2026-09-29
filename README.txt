UNIT PHOTO FILES — UPDATED OFFLINE VERSION

Files:
- index.html: app
- manifest.json: install metadata
- sw.js: offline app-shell cache
- icon.svg: home-screen icon

Deploy all files at the ROOT of a public HTTPS static site (for example GitHub Pages).
Then open the HTTPS site in Chrome and choose Install app / Add to Home screen.

Features:
- Classes > Units > Subunits > Exercises
- Save multiple question/answer photos in the selected folder
- IndexedDB local photo storage for offline use on this browser/device
- Rename/delete folders and photos
- JSON backup export/import

Important:
- This is a web app/PWA, not an Android APK.
- First open requires internet to load the hosted app and install/cache it.
- Photos are stored on this device/browser. Clearing browser data or uninstalling may remove them; export backups regularly.
- If the old GitHub repository contains a ZIP, remove it if you want; upload these files individually and overwrite the old index.html, manifest.json, sw.js, and icon.svg.
