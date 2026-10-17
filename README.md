# RehabTrack — Rehabilitation Exercise Tracker

A responsive, single-page rehabilitation exercise tracking demo. It uses plain HTML, CSS and JavaScript so you can open it directly without installing packages or configuring a backend.

## Features
- Dashboard with session, exercise, minutes and weekly consistency summaries
- Prescribed exercise list with name, category, duration, sets, reps and notes
- Add custom exercises from your clinician-approved plan
- Log completed sessions with date, duration and sets/reps
- Session history and seven-day activity charts
- Responsive desktop and mobile navigation
- Local persistence using browser localStorage (data stays in this browser/device)

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser. No build step is required.
3. Add exercises matching your clinician's instructions, then use **Log** to record completed sessions.

For a local development server, run `python -m http.server 8000` in this folder and open http://localhost:8000.

## Deploy with GitHub Pages
1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Wait for the deployment status/link to appear in the Pages section.

## Important
This is a demonstration tracker, not a medical device or source of medical advice. Starter exercises are sample data only; use the plan prescribed by a qualified healthcare professional. This demo has no backend, accounts, cloud sync, or therapist portal. Data stored in localStorage is not automatically shared across devices.
