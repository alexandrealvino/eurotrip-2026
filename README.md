# Eurotrip 2026 — Travel Dashboard

Interactive visualization for the Europe trip (Jun 17 – Jul 11, 2026).

## Travelers
- **Alexandre** 🔵 — Full trip (25 days)
- **Lucas** 🟢 — Italy + Menorca + Ibiza + Riviera
- **David** 🟡 — Ibiza + Riviera

## Route
Florence → Rome → Positano/Amalfi → Sorrento → Capri → Pompeii/Naples → Baleares/Menorca → Ibiza → Nice/Côte d'Azur

## How to use

1. Open `index.html` in a browser
2. Data lives in `data/itinerary.json` — edit to update
3. Drop images in `assets/` subdirectories for placeholders

## Folder Structure

```
assets/
├── cities/           # City photos (florence.jpg, rome.jpg, etc.)
├── events/           # Show/venue photos
├── accommodations/   # Airbnb/hotel screenshots
└── hero/             # Banners, header images
data/
└── itinerary.json    # All trip data (single source of truth)
index.html            # Interactive dashboard
```

## Features
- 🗺️ Interactive Leaflet map with route line
- 📅 Expandable timeline with accommodation links
- 👥 Who's-where overlap calendar
- 🎵 Event cards with ticket links
- ✅ To-do tracker
- 💰 Budget estimator
