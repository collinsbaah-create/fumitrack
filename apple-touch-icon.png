# FumiTrack Pro — Deployment Guide

## Files in this folder
```
fumitrack/
├── FumiTrack_Office.html    ← Office dashboard (admin)
├── FumiTrack_Officer.html   ← Field officer entry app
├── manifest_office.json     ← PWA manifest for office
├── manifest_officer.json    ← PWA manifest for officer
├── sw.js                    ← Service worker (offline support)
├── icon-192.png             ← App icon (small)
├── icon-512.png             ← App icon (large)
├── apple-touch-icon.png     ← iOS home screen icon
└── README.md                ← This file
```

---

## Step 1 — Get a free JSONBin account
1. Go to https://jsonbin.io and sign up free
2. Go to **API Keys** → copy your **Master Key**

---

## Step 2 — Host the files (GitHub Pages — free)
1. Go to https://github.com and create a free account
2. Click **New Repository** → name it `fumitrack` → set to Public → Create
3. Upload ALL files in this folder to the repository
4. Go to **Settings → Pages → Source → main branch → Save**
5. GitHub gives you a URL like: `https://yourusername.github.io/fumitrack/`

---

## Step 3 — Set up the Office Dashboard
1. Open: `https://yourusername.github.io/fumitrack/FumiTrack_Office.html`
2. Enter your JSONBin Master API Key
3. Leave Bin ID blank → click **Open Dashboard**
4. A new database is created → **copy the Bin ID shown**
5. Your office dashboard is live ✅

---

## Step 4 — Set up the Officer App (once, by admin)
1. Open: `https://yourusername.github.io/fumitrack/FumiTrack_Officer.html`
2. Enter the same API Key and the Bin ID from Step 3
3. Click **Save & Open App**
4. Setup is done — credentials are saved on that device ✅

---

## Step 5 — Officers install on their phones

### Android (Chrome)
1. Open the officer URL in Chrome
2. Tap ⋮ menu → **Add to Home Screen** or **Install App**
3. Tap Add → icon appears on home screen

### iPhone (Safari only)
1. Open the officer URL in **Safari** (not Chrome)
2. Tap the Share button (box with arrow)
3. Tap **Add to Home Screen** → Add
4. Icon appears on home screen

### Works full screen — no browser bars ✅

---

## Daily Use

**Officers:** Open FumiTrack icon → choose tab:
- **📦 Log Movement** — when a bag moves to a new location
- **🔄 Update Status** — after offloading grain (bag stays, status changes)

**Offline:** Works with no internet. Entries queue up and sync automatically when signal returns.

**Office:** Dashboard auto-refreshes every 30 seconds. All 3 viewing devices see the same live data.

---

## Adding / Editing Officers or Hub Names
Go to Office Dashboard → **⚙️ Settings** tab
- Add, rename, or remove field officers
- Rename any hub to its actual location name
- Hit Save — syncs to all devices instantly
