# Tiki Tracker — Workout PWA

A progressive web app for tracking lifting workouts week by week.

## Features

- Create a weekly workout plan (Mon–Sun)
- Add exercises with sets and reps
- Track weight progression each week in expandable dropdowns
- All data saved locally on your device
- Works offline once installed
- lbs/kg toggle

## Setup (Deploy to iPhone)

### 1. Generate icons

Open `generate-icons.html` in a browser. Right-click and save:
- The smaller canvas as `icon-192.png`
- The larger canvas as `icon-512.png`

Save both in this folder (next to index.html).

### 2. Create a GitHub repo

Go to https://github.com/new and create a **public** repository (e.g. `workout-tracker`).

### 3. Push files

```bash
cd tools/workout-tracker
git init
git add .
git commit -m "Initial PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/workout-tracker.git
git push -u origin main
```

### 4. Enable GitHub Pages

- Go to your repo → Settings → Pages
- Source: main branch, / (root)
- Save and wait ~1 minute

### 5. Install on iPhone

- Open `https://YOUR_USERNAME.github.io/workout-tracker/` in Safari
- Tap Share → "Add to Home Screen"
- Done — full-screen app, works offline

## Usage

1. Tap a day to open it
2. Name your workout (e.g. "Push Day")
3. Add exercises with sets/reps
4. Each session, expand an exercise and tap "Log This Week"
5. Fill in the weight — previous weeks stay visible for tracking progression
