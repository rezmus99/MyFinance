MYFINANCE PWA — INSTALLATION

Contents:
- index.html: dashboard
- manifest.json: app identity, standalone display and icon settings
- sw.js: offline app-shell cache
- icon-192.png and icon-512.png: custom MyFinance icons
- icon-maskable-512.png: Android adaptive icon

INSTALL:
1. Upload/extract this entire folder to an HTTPS web host. Keep the files together.
2. Open the hosted index.html URL in Chrome on Android.
3. Open Chrome's three-dot menu and choose Install app (or Add to Home screen).
4. Confirm installation and launch MyFinance from the home screen.

PWA INSTALLATION AND SERVICE WORKERS REQUIRE HTTPS (localhost is allowed for testing).
Opening index.html directly from Downloads will run the dashboard but will not enable
PWA installation or service-worker offline caching.

DATA:
Transactions and budgets are saved in browser localStorage; receipt images are saved
in IndexedDB. Data stays in that browser/device. Export backups regularly.
