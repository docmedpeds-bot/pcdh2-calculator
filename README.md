# PCDH 2.0 — HDU Network Revenue Calculator

An interactive web application for Health Data Utility (HDU) networks to model their potential revenue from the Patient Centered Data Home 2.0 national data network.

## Features

- **Payer Mix Bar** — Draggable segments, click-to-edit percentages, always totals 100%
- **Data Availability & Tech Stack** — Indicate what your HIE has; products color-code readiness
- **28 Products** — Elect products across Alerting, Infrastructure, Public Health, Quality, Payment, Social Needs, and New Knowledge
- **Per-Product Controls** — Base fee, volume rate slider, market penetration, quality/SLA score, and factor inputs (studies, quality measures)
- **Live Revenue Estimates** — Updates instantly as parameters change
- **Revenue Breakdown & Charts** — Bar chart, detailed table, data and tech heatmaps
- **Export to CSV** — Download your full revenue model
- **Save Snapshots** — Log sessions for review
- **Admin Panel** — PIN-protected; manage product descriptions, external links, overhead rates, and activity log

## Usage

Open `index.html` in any modern browser. No server or dependencies required — fully self-contained.

## Publishing via GitHub Pages

1. Fork or upload this repository
2. Go to **Settings → Pages**
3. Set Source to **Deploy from branch → main → / (root)**
4. Your calculator will be live at `https://yourusername.github.io/repo-name`

## Admin Access

Access the admin panel by clicking the **PCDH 2.0** badge in the top-left corner of the app.

## Data Source

Built from the *US National HDU Network* business model spreadsheet, referencing the Participant Calculator, Potential Product Listing, and associated data requirement and technical stack tabs.
