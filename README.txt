# Study Tracker PWA

## Deploy with GitHub + Vercel
1. Replace the repository's existing `index.html` with this folder's `index.html`.
2. Add `manifest.json`, `sw.js`, and the complete `icons/` folder to the repository root.
3. Commit the changes. Vercel should deploy automatically if GitHub integration is enabled.
4. Open the HTTPS website in Chrome and use the browser's Install app option.

## Notes
- Service workers require HTTPS (localhost is also allowed for development).
- Offline mode can display the cached app shell. Firebase login, cloud sync, and other network-dependent features still require internet.
- After changing the app, update the service worker cache name (for example, `study-tracker-v2`) when you need to force a fresh cache.
