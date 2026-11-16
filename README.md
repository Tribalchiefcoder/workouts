# Home Dumbbell Aesthetic

A simple, mobile-friendly workout website with a 5-day home training plan that needs only **dumbbells and a resistance tube**. No bench, no gym, no sign-up.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20the%20site-4f8cff?style=for-the-badge)](https://tribalchiefcoder.github.io/workouts/)

**Live demo:** [https://tribalchiefcoder.github.io/workouts/](https://tribalchiefcoder.github.io/workouts/)

Open it on your phone and use *Add to Home Screen* to launch it like an app.

---

## What it can do

- **5-day plan (Monday to Friday):** each day shows its muscle focus, every exercise, and the sets, reps and rest time.
- **Tick off exercises:** check each exercise as you finish it. A progress bar shows how much of the day is done, and your ticks are saved on your device, so they survive a page refresh.
- **Rest timer:** tap **Start Workout** or any exercise's rest button for a countdown with +15s / −15s adjustments. It beeps and vibrates when time is up, and stays accurate if your phone screen sleeps.
- **Exercise library:** a searchable grid of all 34 exercises. Filter by muscle group (Chest, Back, Shoulders, Arms, Legs, Core) and by equipment (Dumbbell, Resistance Tube, Bodyweight).
- **Exercise details:** tap any exercise to see a looping demo, step-by-step instructions, target muscles, equipment needed, a form cue and a common mistake.
- **Supersets and finisher:** supersets and the Friday finisher circuit are labelled so you know when to skip the rest.
- **Dark, responsive design:** a sidebar on desktop and a bottom tab bar on mobile.

## The weekly plan

| Day | Focus |
| --- | --- |
| Monday | Push: chest, shoulders, triceps |
| Tuesday | Pull: back, biceps, rear delts |
| Wednesday | Legs + core |
| Thursday | Upper V-taper: shoulders, back, arms, core |
| Friday | Lower body + conditioning |

Mid-week break option: Push / Pull / Legs / Rest / Upper / Lower / Rest. Keep at least 48 hours between sessions that hit the same muscle group.

## Run it yourself

The whole site is one file, `index.html`. There is nothing to install or build.

1. Download or clone this repo.
2. Open `index.html` in a browser.

To host it free on GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Customise the plan

Open `index.html` and edit the two arrays at the top of the `<script>`:

- `LIB`: the exercise library (name, muscle group, equipment, form cue, common mistake).
- `PLAN`: the weekly schedule (exercise, sets, reps, rest seconds, optional note).

## Built with

- Plain HTML, CSS and JavaScript, with no frameworks and no backend.
- Demo images and instructions from the open [Free Exercise DB](https://github.com/yuhonas/free-exercise-db). Where it has no exact match, the exercise page shows the closest one and says so.
- The API response is cached in your browser, so repeat visits are fast.

## Disclaimer

Consult a physician before starting any new exercise program.
