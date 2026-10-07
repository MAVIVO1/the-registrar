# The Registrar

Recruiter-facing student information system with a dual-view roster (card
catalog + ledger), an animated SVG GPA gauge, full CRUD with modals, CSV
export, and a navy/parchment/brass design system.

## Tech stack

Pure vanilla HTML/CSS/JS — **no build step, no dependencies, no backend.**
Everything runs in a single `index.html` file using `localStorage` for
persistence.

## Features

- **Dual-view roster**: toggle between a card-catalog grid and a spreadsheet-style ledger
- **Animated SVG GPA gauge**: an arc gauge (and live stat panel) that animates in based on the class average GPA
- **Full CRUD**: add, edit, and delete student records through a modal form
- **CSV export**: one click downloads the full roster as a CSV
- **Rubber stamp animation**: a satisfying "Enrolled / Updated / Removed" stamp plays on every save/delete
- 10 pre-seeded Ethiopian university students so the app isn't empty on first load

## Getting started

No install required. Just open `index.html` in any modern browser:

```bash
open index.html      # macOS
start index.html      # Windows
```

Or serve it locally:

```bash
npx serve .
```

## Design system

- **Palette**: deep navy (`#10142b`), parchment (`#f3ead9`), brass gold (`#c9a24a`)
- **Typography**: Fraunces (display/serif headings) + Inter (body) + IBM Plex Mono (data/labels)

## Project structure

```
the-registrar/
└── index.html   # everything — markup, styles, and logic in one file
```
