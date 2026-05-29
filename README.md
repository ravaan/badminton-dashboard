# 🏸 Badminton Session Dashboard

A personal badminton analytics dashboard tracking session performance with Garmin data.

## Live Dashboard

**[View Dashboard](https://ravaan.github.io/badminton-dashboard)**

## Features

- 📊 **Session Overview** — Total sessions, calories burned, average duration, best training load
- 📈 **Performance Trends** — Duration, calories, and training load over time
- ❤️ **Heart Rate Analysis** — Average vs Max HR comparison, HR zone distribution
- 💪 **Training Effect** — Aerobic and anaerobic training effect tracking
- ⚡ **Intensity Breakdown** — Moderate vs vigorous minutes per session
- 🔋 **Body Battery Impact** — How much each session costs in body battery
- 💧 **Hydration Tracking** — Estimated water loss per session

## Data Source

Data is synced automatically from Garmin Connect via the nightly cron job. Sessions are identified by `activityId` for deduplication.

## Auto-Update

The dashboard auto-updates when new sessions are pushed to `data/sessions.json`. The nightly Garmin sync script handles this automatically.

## Tech Stack

- Pure HTML/CSS/JavaScript (no build tools)
- [Chart.js](https://www.chartjs.org/) for visualizations
- GitHub Pages for hosting

---

Built with ❤️ for tracking badminton gains 🏸
