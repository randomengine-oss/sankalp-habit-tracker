# Sankalp — संकल्प
### Your personal daily habit reset

A fully offline, PWA habit tracker built for personal use. No login, no server, no Firebase — just you and your habits.

---

## 📁 Files to Upload to GitHub

```
index.html      ← Main Core File
manifest.json   ← PWA manifest
sw.js           ← Service worker (offline support)
icon-192.png    ← App icon (generate from the app or use any 192x192 PNG)
icon-512.png    ← App icon large (512x512 PNG)
```

> **Note:** `icon-192.png` and `icon-512.png` are auto-generated inside the app using Canvas.  
> 

---

## 🚀 GitHub Pages Setup

1. Create a new **public** repository on GitHub
2. Upload all 5 files above. 
3. Go to **Settings → Pages**
4. Source: `Deploy from branch` → Branch: `main` → Folder: `/ (root)`
5. Click **Save** — wait ~60 seconds
6. Your URL: `https://YOUR_USERNAME.github.io/REPO_NAME`

---

## 📱 Install on iPhone

1. Open the URL in **Safari** (not Chrome)
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Name it **Sankalp** → tap **Add**

Done — it opens full-screen like a native app.

---

## 📱 Install on Android

1. Open the URL in **Chrome**
2. Tap the **3-dot menu** → **"Add to Home screen"**  
   or Chrome will show an automatic install banner
3. Tap **Install**

---

## 💾 Data Storage

All data is stored in **localStorage** on your device:
- Habits, history, streaks, coins — all local
- Works 100% offline after first load
- Clearing browser data will wipe it — use **Settings → Export Backup** to save a JSON file

---

## ✨ Features

- ✅ 20 original features (setup, rings, streaks, timer, vault, AI summary, WhatsApp share...)
- 📅 Day scheduling (Mon/Wed/Fri habits)
- 🔢 Counter habits (drink 8 glasses)
- 🚫 Bad habit tracking (quit mode)
- ⏰ Time-of-day grouping (Morning / Evening)
- 🗓️ GitHub-style heatmap
- 📊 Analytics with bar charts
- 🌙 Dark mode
- 🔔 Browser notifications
- 📲 Full PWA — installs like a native app

---

*Built with pure HTML/CSS/JS — no frameworks, no dependencies, no internet required.*
