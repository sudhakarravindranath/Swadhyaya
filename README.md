# Swadhyaya — स्वाध्याय
## Deployment Guide

### Files in this package
- `index.html`     — Main application
- `manifest.json`  — PWA manifest (name, icon, theme)
- `sw.js`          — Service worker (offline caching, push notifications)
- `icon-192.png`   — Home screen icon (192×192)
- `icon-512.png`   — Splash screen icon (512×512)

---

### Deploy to Netlify (recommended, free)

1. Go to https://netlify.com and sign up (free)
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag the entire `swadhyaya` folder onto the upload area
4. Netlify gives you a URL like `https://swadhyaya-abc123.netlify.app`
5. Open that URL on your Android phone in Chrome
6. Tap the three-dot menu → **"Add to Home screen"**
7. Confirm — the Swadhyaya icon now appears on your home screen

---

### What works in Segment 1
- Full app shell with navigation (Home, Topics, Saved, Search)
- All 10 topic categories with subcategories, fully editable
- Add, edit, delete categories and subtopics
- All data persists in phone storage (localStorage)
- Installable on Android home screen
- Works offline once installed
- Push notification permission (bell icon in header)

### What comes in later segments
- Segment 2: RSS feed integration (trusted sources per category)
- Segment 3: AI-powered content discovery layer
- Segment 4: Push notifications with new content alerts
- Segment 5: Save, bookmark, and filter content

---

### Custom domain (optional)
Netlify allows you to set a custom domain if desired.
The default `.netlify.app` URL works perfectly for personal use.
