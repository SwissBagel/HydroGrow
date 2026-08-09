# HydroGrow

A self-contained hydroponic growing assistant that runs entirely in your browser. No build tools, no dependencies, no server — just open the HTML file.

## What It Does

HydroGrow gives hobbyist hydroponic growers everything they need to plan, execute, and track their grows in one place:

- **Dashboard** — Reference data for 20 crops across 8 growing systems. pH, EC, temperature, light requirements, system-specific setup details, spacing, and troubleshooting — all tailored to your selected crop and system combination.
- **Harvest Planner** — Timeline from germination to harvest with `.ics` calendar export and configurable reminders.
- **Nutrient Calculator** — Dosing calculations for 3-Part (Flora Series) and 2-Part (A/B) nutrient systems. Accounts for tank size, growth stage, system type, tap water EC baseline, and displays both EC and PPM.
- **Companion Planting** — Compatibility matrix showing which crops can share a reservoir based on overlapping pH, EC, and temperature ranges.
- **Nutrient Deficiency Diagnosis** — Interactive flowchart that walks you from visible symptoms to nutrient identification and hydroponic-specific fixes in three steps.
- **Grow Journal** — Multi-grow tracking with pH, EC, temperature logging, SVG charts with ideal range bands, equipment toggles (fan/airstone) that adjust temperature tolerances, and JSON export/import backup.

## Supported Crops

Leafy Greens: Lettuce, Spinach, Kale, Arugula, Swiss Chard, Bok Choy, Watercress

Herbs: Basil, Cilantro, Mint, Parsley, Dill, Chives, Oregano, Thyme

Fruiting: Strawberries, Tomatoes, Cucumbers

Specialty: Microgreens, Green Onions

## Supported Systems

DWC (Deep Water Culture), NFT (Nutrient Film Technique), Ebb & Flow, Drip, Aeroponics, All-in-One, Kratky, Vertical Tower

Each crop includes a compatibility rating (Excellent / Good / Workable / Not Recommended) for every system, along with system-specific setup details and relative growth speed notes.

## Quick Start

1. Download `hydroponic-assistant-v22.html`
2. Open it in any modern browser
3. Select a crop and system
4. Start growing

That's it. No install, no account, no internet required (except for the Google Fonts import, which degrades gracefully).

## Screenshots

*Coming soon*

## Data Storage

Grow journal data is stored in your browser's `localStorage` under the key `hydrogrow_journal`. Use the Export button in the Journal tab to back up your data as JSON, and Import to restore it. Nothing leaves your browser.

## Features at a Glance

| Feature | Details |
|---|---|
| Crops | 20 crops with full pH, EC, temp, light, and stage data |
| Systems | 8 hydroponic systems with per-crop compatibility ratings |
| Units | Toggle between °F/°C and EC/PPM anywhere in the app |
| Themes | Dark and light mode |
| Calculator | 3-Part and 2-Part nutrient dosing with tap water baseline |
| Diagnosis | Universal nutrient deficiency flowchart (13 endpoints) |
| Journal | Multi-grow tracking with charts, backlog entry, and equipment adjustments |
| Planner | Harvest timeline with .ics calendar export |
| Companions | Reservoir compatibility scoring based on pH, EC, and temp overlap |
| Mobile | Responsive layout for phone and tablet use |
| Accessibility | Keyboard focus styles, ARIA labels, color-blind safe indicators |

## Tech Stack

- Vanilla JavaScript — no frameworks
- Single HTML file — CSS and JS inline
- SVG charts — no charting library
- CSS custom properties — dark/light theming
- localStorage — journal persistence
- Zero external dependencies (one optional Google Fonts import)


## Built With AI, Verified By Humans

This tool was written with AI assistance (Anthropic Claude) and reviewed, tested, and validated by a human throughout every iteration.

## Contributing

This is a personal project, but suggestions and bug reports are welcome via Issues. If you're a hydroponic grower and something doesn't match your real-world experience, I especially want to hear about it — this app is grounded in practical growing, not textbook idealism.

## License

MIT
