IRL XP PWA starter

Files:
- index.html: current IRL XP v3 prototype with PWA metadata
- manifest.webmanifest: install name, app display mode, theme
- sw.js: basic offline app-shell cache
- icon.svg: app icon

Android install:
1. Upload all files to a static HTTPS host, keeping them together in the same folder.
2. Open the hosted site in Chrome.
3. Open Chrome's ⋮ menu and choose "Install app" or "Add to Home screen" (wording can vary).
4. Launch IRL XP from the home-screen icon.

Important:
- A local file opened as file:// cannot register a service worker or be installed as a PWA. It must be hosted on HTTPS (or localhost).
- Progress is still stored locally in the browser. This package does not add real accounts or a shared leaderboard.
- Tidying proof images remain in local browser storage and are not uploaded to a server.
