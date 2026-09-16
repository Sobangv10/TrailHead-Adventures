# TrailHead 🏕️

A multi-page adventure travel and outdoor gear website, built with **HTML** and **Tailwind CSS** (via the Tailwind CDN, no build step or JavaScript required).

TrailHead is a fictional adventure travel brand offering guided expeditions, eco-friendly stays, gear rentals, and safety resources for people who plan their year around a trailhead.

## Pages

The site is organized into four main sections, each with its own dropdown in the navbar:

- **Expeditions** — Mountain Trekking Routes, River Kayaking & Rafting, Forest Camping Safaris, Desert Survival Camps
- **Stays & Lodges** — Eco-Friendly Cabins, Mountain Glamping Tents, Treehouse Resorts, Wilderness Hostels
- **Gear & Rentals** — Camping & Tent Gear, Trekking Apparel & Boots, GPS & Safety Equipment, Complete Backpacking Packages
- **Guides & Safety** — Certified Local Guides, Trail Maps & GPX Downloads, Wilderness First Aid Guide, Weather & Avalanche Alerts

Plus a homepage (`index.html`) and category landing pages for each section above.

## Tech

- Pure HTML5
- [Tailwind CSS](https://tailwindcss.com/) via the browser CDN (`@tailwindcss/browser`)
- No JavaScript — interactive elements (dropdowns, mobile menu, carousels) are built entirely with CSS `:checked` / `peer` selectors on hidden checkbox/radio inputs
- Fully responsive (mobile, tablet, desktop)

## Project structure

```
TrailHead-Adventures/
├── index.html
├── expeditions.html
├── mountain-trekking-routes.html
├── river-kayaking-rafting.html
├── forest-camping-safaris.html
├── desert-survival-camps.html
├── stays-lodges.html
├── eco-friendly-cabins.html
├── mountain-glamping-tents.html
├── treehouse-resorts.html
├── wilderness-hostels.html
├── gear-rentals.html
├── camping-tent-gear.html
├── trekking-apparel-boots.html
├── gps-safety-equipment.html
├── complete-backpacking-packages.html
├── guides-safety.html
├── certified-local-guides.html
├── trail-maps-gpx-downloads.html
├── wilderness-first-aid-guide.html
├── weather-avalanche-alerts.html
└── img/
    └── (all page images)
```

## Running locally

No build tools needed — just clone and open in a browser:

```bash
git clone https://github.com/Sobangv10/TrailHead-Adventures.git
cd TrailHead-Adventures
```

Then open `index.html` directly in your browser, or serve it locally:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Notes

- All images referenced in the HTML are expected inside an `img/` folder at the project root — add your image assets there before deploying.
- Built as a learning/portfolio project.
