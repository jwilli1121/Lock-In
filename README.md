# Lock-In: Personal Growth Dashboard

Lock-In is a local-first personal growth dashboard for habits, health, workouts, finances, achievements, insights, and progress reporting.

## Live Demo

After enabling GitHub Pages:

`https://jwilli1121.github.io/lock-in-personal-growth-dashboard/`

## Features

- Positive and negative habit tracking
- Streaks, XP, Life Level, and exercise-neutral achievements
- Sleep, steps, weight, hydration, calorie, and protein logging
- Structured workout logs with sets, reps, weight, notes, ratings, and personal records
- Income, expense, transaction, and budget tracking
- Life Score, period insights, and weekly reports
- Calendar history, progress charts, themes, and JSON backup/restore

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas charts
- Browser Local Storage
- GitHub Pages

## Repository Structure

```text
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── screenshots/
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Run Locally

For the repository build, run a small local web server from the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

Alternatively, use the separate standalone HTML release, which contains all CSS and JavaScript in one file and can be opened directly.

## Data and Privacy

Each visitor gets a separate local copy. App data is stored in that visitor's browser using Local Storage. It is not shared with other visitors or uploaded to a server. Clearing browser storage can remove entries, so export backups regularly.

Do not enter sensitive banking, authentication, medical, or identity information in a public demo.

## AI-Assisted Development

This project was created through AI-assisted development. Jonathan Williams defined the product vision, requirements, workflows, scoring systems, interface changes, testing feedback, and release direction. The application implementation was generated and refined with AI assistance rather than written manually line by line.

## Compatibility

The original Local Storage key is preserved. Existing Lock-In data in the same browser and site origin remains compatible. Universal starter habits appear only when no saved Lock-In state exists.

## Author

Jonathan Williams
