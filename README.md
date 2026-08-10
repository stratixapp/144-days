# 144 Days — GitHub Pages + Mobile Install

## 1. Push to GitHub
1. Create a new repo (e.g. `144-days`).
2. Upload all 7 files from this folder to the repo root:
   `index.html`, `manifest.json`, `service-worker.js`, `photo.jpg`,
   `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.
3. Repo → **Settings → Pages → Branch: main / (root)** → Save.
4. Your app goes live at `https://<username>.github.io/144-days/`.

## 2. Install on phone
- **Android (Chrome):** open the link → menu (⋮) → **Add to Home screen** / **Install app**.
- **iPhone (Safari):** open the link → Share icon → **Add to Home Screen**.

It'll open full-screen, no browser bar, with your photo as the app icon, and it keeps working offline once loaded once.

## What's inside
- Locked to a mobile-app layout (max ~480px wide, centered) — no desktop stretching, just a clean phone-sized experience whether you open it on your phone or a browser.
- 144-day countdown (Aug 10 → Dec 31, 2026) with live days/hours/min/sec timer.
- Every date is labelled "Day 1" through "Day 144", real calendar date shown alongside.
- The moment a day finishes, it fades away with a 3D vanish animation and disappears from the grid — only the days still ahead of you stay visible. (Toggle the "Completed" filter to see finished days again.)
- Weekly off — set manually in Settings (persists in the browser).
- Indian public holidays pre-loaded, toggle any off in Settings.
- 144 daily quotes, one per day, swipeable/browsable, in an elegant italic serif.
- Every calendar date shows one of your 3 photos as a background (cycling through them), with a 3D tilt on hover/tap.
- A live analog clock with your photo as the watch face, animated hour/minute/second hands.
- **Background music** — tap the 🎵 icon in the header. It's a soft ambient pad generated live in the browser (no audio file, works offline, loops forever) with occasional gentle chime twinkles. Your choice is remembered next time you open the app.
- Soft floating hearts drifting in the background, romantic serif headings, warmer rose/gold accents.
- 3D depth throughout — tilting cards, layered shadows, glass bevels on the timer boxes, milestones, and today card.
- Your photo on the intro screen + as the home-screen app icon.

Uses Google Fonts (Playfair Display) via CDN — needs an internet connection the first time it loads; after that the service worker caches everything for offline use.
