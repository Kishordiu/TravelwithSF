# Travel with StreetForge

> **Discover. Shape. Go.**

Travel with StreetForge is a browser-based travel-planning MVP that takes a user from destination discovery to itinerary assembly and a simple trip-budget estimate.

The current build is intentionally dependency-free so it can be hosted as a static site without API keys.

## Product surface

- Curated destination discovery
- Search by destination, region or travel theme
- Theme filters
- Add/remove destinations from an itinerary
- Automatic planned-day calculation
- Adjustable trip length from 1–14 days
- Base budget estimation from planning data
- Copyable trip brief
- Responsive desktop/mobile interface
- StreetForge product identity
- No account or backend required

## Architecture

- `index.html` — product shell and SEO/social metadata
- `style.css` — visual system and responsive layout
- `app.js` — destination catalogue, filtering, itinerary state and budget logic
- `favicon.svg` — project mark

The current destination catalogue is embedded demo data. A production data layer can later connect maps, transport, accommodation, weather and places APIs behind isolated service adapters.

## Run locally

```bash
git clone https://github.com/Kishordiu/TravelwithSF.git
cd TravelwithSF
python -m http.server 8000
```

Open `http://localhost:8000`.

## Product roadmap

- Live map and route planning
- Transport and accommodation integrations
- Weather-aware itinerary planning
- Collaborative shared trips
- AI-assisted trip recommendations
- Saved trips and accounts
- Calendar and PDF export

## Status

**Major project · Functional trip-planning MVP**

Built and maintained by **K. Kishor Kumar**.

[GitHub @Kishordiu](https://github.com/Kishordiu)
