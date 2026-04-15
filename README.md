# Sketch3D

A 3D sketching tool — installable as a Progressive Web App.

## 🚀 Deploy on GitHub Pages

1. Push all files to a GitHub repository (keep the folder structure as-is).
2. Go to **Settings → Pages** in your repo.
3. Under *Source*, select **Deploy from a branch** → `main` → `/ (root)`.
4. Save. Your app will be live at `https://<your-username>.github.io/<repo-name>/sketch3d_v5_11.html`.

## 📁 File structure

```
├── sketch3d_v5_11.html   ← main app (already wired for PWA)
├── manifest.json          ← PWA manifest
├── sw.js                  ← service worker (offline support)
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## 📲 Installing as a PWA

- **Android / Chrome**: tap the browser menu → *Add to Home Screen*
- **iOS / Safari**: tap Share → *Add to Home Screen*
- **Desktop Chrome/Edge**: click the install icon in the address bar

The app caches itself on first load and works fully offline after that.
