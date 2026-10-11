IRONLOG — YOUR PERSONAL GYM TRACKER
===================================

WHAT'S INCLUDED
- Workout routines: Push, Pull, Legs, Chest + Back
- Log sets, weights, reps, and completed sets
- Add/remove exercises and sets
- Rest timer
- Workout history
- Personal bests by heaviest logged set
- kg/lb setting
- Export/import JSON backups
- Offline cache (after the app is opened online once)
- Data saved in the browser on this device

IMPORTANT
This is a static Progressive Web App (PWA). To install it as a Home Screen app with
offline support, the files must be served from an HTTPS website. Opening index.html
directly from Files is fine for a quick test, but service workers/offline installation
will not work reliably from a file:// URL.

EASIEST FREE HOSTING: GITHUB PAGES
1. On a computer, sign in or create a GitHub account at https://github.com
2. Create a new PUBLIC repository, e.g. "ironlog-gym".
3. Upload all files in this folder to the repository root (index.html, manifest.json,
   sw.js, icon-192.png, icon-512.png).
4. In the repository, open Settings > Pages.
5. Under Build and deployment, select "Deploy from a branch", choose "main" and "/ (root)",
   then Save.
6. Wait a minute or two. GitHub will show a URL like:
   https://YOUR-USERNAME.github.io/ironlog-gym/
7. Open that URL in Safari on your iPhone. Visit it once while online.
8. In Safari, tap the Share button (square with arrow pointing up).
9. Scroll and tap "Add to Home Screen". If offered, enable "Open as Web App", then tap Add.
10. Launch IronLog from the new Home Screen icon. Open it online once first so the
    offline files can be cached. Then test Airplane Mode.

IF "ADD TO HOME SCREEN" ISN'T VISIBLE
- In the Share sheet, scroll down and tap Edit Actions if available.
- Make sure you're opening the website in Safari, not an in-app browser.

DATA & BACKUPS
- Workout history is saved in local browser storage on the device/browser profile.
- It does not automatically sync to iCloud or other devices.
- Export a backup from Settings regularly. Keep the JSON file somewhere safe.
- Do not clear Safari website data unless you have exported a backup.
- Importing a backup replaces the current data after confirmation.
- Reinstalling or using a different browser may not carry your data over.

PRIVACY
The app does not send your workout data to a server. Hosting serves the app files only.
Your logs stay in the browser storage on your device, unless you export and share a backup.

LIMITATIONS
- This is a personal web app, not an App Store app.
- Offline caching is best-effort and starts after the first online visit.
- If browser storage is cleared, local logs can be lost; use backups.
- Timer countdown works while the page is active; iOS may suspend web pages in the background.
