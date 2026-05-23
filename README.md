# ⚡ RunTrack — Running Schedule PWA

A standalone Progressive Web App for tracking your running schedule. Works offline, installs to your home screen, and lets you import new schedules from .ics files.

---

## How to Host on GitHub Pages (Free)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click the **+** icon (top right) → **New repository**
2. Name it `runtrack` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the Files
1. On the repository page, click **uploading an existing file**
2. Drag and drop all 4 files into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

### Step 5 — Get Your URL
After about 1–2 minutes, GitHub Pages will publish your app at:
```
https://YOUR-USERNAME.github.io/runtrack/
```
You'll see this URL in the Pages settings.

---

## Installing to Your Samsung S23 Home Screen

1. Open Chrome on your S23
2. Navigate to your GitHub Pages URL
3. Tap the **three-dot menu** (⋮) in Chrome's top-right corner
4. Tap **"Add to Home screen"**
5. Name it **RunTrack** and tap **Add**

The app will appear on your home screen and open in full-screen mode (no browser bars), just like a native app. It also works **offline** once installed.

---

## Importing a New Schedule

1. Open the app and tap the **Import** tab
2. Tap **"Select .ics File"** and choose your new schedule file
3. Review the preview (number of events, date range)
4. Tap **"Load Schedule"** to confirm

The app parses standard iCalendar (.ics) files, compatible with schedules exported from Google Calendar, Apple Calendar, Outlook, and AI-generated planning tools.

---

## Features

- **Today view** — Shows your current workout with focus notes, rep counts, and a log button
- **Schedule view** — Full scrollable list of every training day with completion indicators
- **History view** — All completed workouts with your time/pace and notes
- **Import** — Load any new .ics running schedule without needing to rebuild the app
- **Offline support** — Works without internet after first load
- **Local storage** — All data stays on your device, never sent anywhere