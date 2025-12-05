# Gelato Formulator

A mobile-friendly PWA for professional gelato and sorbet recipe formulation.

## Features

- 🍨 Recipe management with real-time formulation stats
- 📊 Sugar%, fat%, MSNF%, total solids%, freezing point calculations
- 🔍 Search and filter recipes by name or type
- ⚖️ Scale recipes in 1000g increments
- ✅ Ingredient checklist for production
- 📦 62 ingredient database with nutritional profiles
- 🔒 PIN protection (default: 0119)
- 📱 Works offline as PWA
- 💾 Auto-merge new recipes on update
- 📤 Export/import data backups
- 📄 CSV/Excel recipe import

## Pre-loaded Recipes

1. Chocolate Sorbet
2. Buttermilk Gelato
3. Chocolate Gelato w/ Callebaut 70.5%
4. Blueberry-Coconut Sorbet
5. Strawberry Gelato
6. Passion Fruit Sorbet
7. Coconut-Vanilla Gelato
8. Salted Caramel Gelato

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
2. Browse recipes in the **Recipes** tab
3. Tap a recipe to view, scale, and check off ingredients
4. Create new recipes with real-time formulation feedback
5. View target ranges in the **Targets** tab

## Add to Home Screen

On mobile, tap Share → Add to Home Screen for app-like experience.

## Data

All data is stored locally in your browser's localStorage. New default recipes are automatically merged on app updates without losing your custom recipes.
