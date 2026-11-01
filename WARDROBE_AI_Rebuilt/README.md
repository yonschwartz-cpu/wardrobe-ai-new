# WARDROBE AI — Rebuilt Web App

A mobile-friendly wardrobe organizer and outfit planner that can be deployed as a static website and added to an iPhone Home Screen.

## Deploy on Vercel
1. Upload the **contents** of this folder to the root of your GitHub repository (not the ZIP and not the enclosing folder).
2. In Vercel, import the GitHub repository.
3. Framework Preset: **Other**.
4. Build Command: leave blank.
5. Output Directory: `.` (or leave the default if Vercel detects the static site).
6. Deploy.

The file `index.html` must be at the repository root.

## Current features
- Closet inventory with category, color, brand, warmth, material, weight, URL, photo and favorite.
- Casual, School, Shabbos and Dressy Casual outfit rules.
- Local weather using browser geolocation and Open-Meteo.
- Outfit history and recent-item rotation.
- Saved product ideas.
- PWA manifest and service worker for Home Screen installation.

## Important limitations
- Closet data is stored locally in this browser/device; there is no account or cloud sync.
- Outfit suggestions use local rules, not a connected generative AI service.
- Product links are saved as notes; they are not automatically analyzed.
- Weather requires internet and location permission.
- When adding many large photos, browser storage limits may apply.
