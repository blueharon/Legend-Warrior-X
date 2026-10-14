# Legend Warriors X — Mobile Edition

This is an installable Progressive Web App (PWA) edition of the supplied game. It keeps the Three.js 3D action RPG and adds a mobile-first HUD, on-screen movement/combat controls, app metadata, an icon, and a service worker for caching the app shell.

## Run locally
Because the game uses JavaScript modules, serve this folder over HTTP rather than opening `index.html` as a file. For example, with Python installed:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Install on a phone
1. Upload this folder to an HTTPS static host (for example, GitHub Pages or another static web host).
2. Open the HTTPS URL in your phone's browser.
3. Android/Chrome: choose **Install app** or **Add to Home screen** from the browser menu.
4. iPhone/iPad/Safari: choose **Share → Add to Home Screen**.

The game loads Three.js from jsDelivr, so the first load and 3D engine require an internet connection. The service worker caches the local app shell, but this is not a fully offline build.

## Controls
Use the on-screen D-pad to move. Tap Strike, Blast, Dash, Jump, Ult, Form, Charge, or Art to fight. Keyboard controls and local co-op remain available on supported devices.

## Native stores
This package is a PWA, not an Android APK or iOS IPA. Publishing to Google Play or Apple's App Store requires an additional wrapper/build and store setup.


## Android landscape mode
The web-app manifest requests `orientation: landscape`, so Android browsers that honor PWA orientation should launch the installed app in landscape. Landscape-specific CSS rearranges the HUD and touch controls for short, wide screens. To apply this change to an already-installed app, redeploy the updated files, reopen the app online, and if necessary remove and reinstall the home-screen app so Android refreshes the manifest.
