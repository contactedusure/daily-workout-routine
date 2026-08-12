# Daily Workout Routine

Mobile-first, single-file web app for a personalized daily workout + pranayam plan (built Aug 2026).

## Live site

Once GitHub Pages is enabled (Settings → Pages → Deploy from a branch → `main` → `/ (root)`):

**https://contactedusure.github.io/daily-workout-routine/**

Open on phone → browser menu → **Add to Home Screen** → works offline like an app.

## What's inside

- **Today** — auto-detects the day and shows the timed checklist (6:45–7:45 AM). Tuesday asks whether yoga class happened and loads the right plan.
- **Moves** — illustrated guide for every exercise (steps + what to avoid).
- **Week** — fixed weekly schedule, travel fallbacks (hotel gym / room-only / tired day), 8-week progression.
- **Food** — simple food rules for sustainable fitness (no strict diet).
- **Track** — weekly grid, day streak, Sunday metrics, notes.

All progress (checkboxes, streaks, notes) saves on the device via localStorage — no account, no server.

## How to update the plan

Everything lives in `index.html`:

- `PLAN` — the weekly schedule and daily checklists
- `MOVES` — exercise guide cards (with inline SVG figures in `FIG`)
- `PRAN` — pranayam block
- `FOOD` / `TIPS` — food rules and consistency tips

Edit, commit, and the Pages site updates automatically.
