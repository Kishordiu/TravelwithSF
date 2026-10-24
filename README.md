![TRAVEL WITH STREETFORGE — bespoke brushed-metal project artwork](./assets/readme-metal-hero.svg)

# TRAVEL WITH STREETFORGE

**A browser-based trip planner for turning destination ideas into a simple, editable itinerary.**

Travel with StreetForge gives a visitor a place to explore a destination catalogue, filter by travel mood, add places to a route, adjust trip duration, and create a shareable planning brief. The current data layer uses explicit demo content rather than live tourism, transport, weather, or accommodation feeds.

## The planning loop

```text
Explore the catalogue
        │
        ▼
Filter by travel mood
        │
        ▼
Choose destinations
        │
        ▼
Shape the route + trip length
        │
        ▼
Review / share the itinerary brief
```

## Design principles

- **Discovery should lead somewhere.** A destination is a starting point for a plan, not just a card.
- **The itinerary stays editable.** The visitor can shape the route and trip duration.
- **Budget belongs in the planning loop.** Cost context should help a traveller compare options, not appear as a detached afterthought.
- **Demo data stays visible as demo data.** Real-world availability and prices require reliable data providers.

## Run locally

This is a static HTML, CSS, and JavaScript project; no package installation is required.

```bash
git clone https://github.com/Kishordiu/TravelwithSF.git
cd TravelwithSF
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## Current scope

This repository does not guarantee live hotel availability, transport schedules, weather forecasts, booking, or verified real-time prices. Check destination requirements and all travel arrangements with authoritative providers before making or paying for plans.

---

<p align="center"><sub>DIU FOUNDRY · TRAVEL EXPERIENCE / PRODUCT DESIGN</sub></p>
