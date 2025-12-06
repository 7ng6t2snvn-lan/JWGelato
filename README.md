# Shot Tracker

A mobile-friendly PWA for tracking peptide doses and schedules.

## Features

- 📅 Daily dose tracking with calendar view
- 💉 Reconstitution calculator with visual syringe
- 📦 **Inventory tracking** — Track vials, remaining amounts, auto-deduct on dose
- 📊 97 peptide database with purpose categories (Healing, Muscle, GH Release, Fat Loss, Cognitive, Immune, etc.)
- 🔒 PIN protection (default: 0119)
- 🔴 **Lock button** — Red exit button to lock app from any screen
- 📱 Works offline as PWA
- 💾 Local storage persistence
- 📤 Export/import data backups

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings** → **Pages**
3. Set source to **main** branch, root folder
4. Save — your site will be live at `https://yourusername.github.io/repo-name/`

## Files

- `index.html` — Main app (self-contained)
- `manifest.json` — PWA manifest
- `icon-192.png` — App icon (192x192)
- `icon-512.png` — App icon (512x512)

## Usage

1. Open the app and enter PIN: **0119**
2. View/manage schedules in the **Schedules** tab
3. Log doses in the **Today** tab — auto-deducts from inventory
4. Track vials in the **Inventory** tab
5. Use the **Calc** tab for reconstitution math
6. Browse peptides by category or purpose in the **Database** tab
7. Tap the red **Lock** button to exit and lock the app

## Add to Home Screen

On mobile, tap Share → Add to Home Screen for app-like experience.

## Data

All data is stored locally in your browser's localStorage. Use Export/Import in Settings to backup your data.
