# Blind — Colour Lens

Android-first colour identification PWA with live camera, photo sampling, manual colour entry, palette extraction, 242 approximate named references, local saved colours and CSV export. Images stay on the device.

## Deploy
In Settings > Pages, select Deploy from a branch, main, / (root), then Save. Open https://aksharghatole.github.io/Blind/ after deployment. In Android Chrome, allow camera access and use Add to Home screen / Install app. Offline support is available after a successful online load and cache installation.

## Local testing
Run `python -m http.server 8000` and open http://localhost:8000. Camera requires HTTPS or localhost. This is not a native APK. Colour names are approximate; lighting, camera processing and image downsampling affect accuracy. Saved colours are local to your browser, so export a CSV before clearing site data.

The application is bundled into index.html for easy deployment. Android camera and installation require device testing.
