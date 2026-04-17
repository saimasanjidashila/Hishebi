Hishebi v21 - App-ready web source

Files:
- index.html              Main app source
- manifest.webmanifest   PWA manifest
- manifest.json          Compatibility manifest copy
- sw.js                  Service worker
- icon-192.png           App icon
- icon-512.png           App icon

How to run locally:
1. Serve this folder from a local web server. Do not open index.html with file://
2. Example with Python:
   python -m http.server 8000
3. Open http://localhost:8000 on your browser.

How to install on Android:
1. Host this folder on HTTPS or run on localhost.
2. Open the app in Chrome.
3. Use the + button or browser menu > Add to Home screen / Install app.

Notes:
- This is the v21 codebase with the install-flow fixes.
- The app stores data locally in the browser unless cloud sync is configured.
