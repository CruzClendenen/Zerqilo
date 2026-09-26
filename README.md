# Zerqilo v5

Zerqilo is a local-first training journal..

**Slogan:** Every rep remembered.

## Added in v5
- Goal-based Program Builder: generate a multi-day program from training goal, days/week, experience, session length, priority exercise, and optional target.
- Export JSON backups and CSV workout data.
- Import/restore JSON backups.
- Edit and delete workouts from History.
- Save, load, and delete workout templates.
- Progress chart for estimated 1RM over time.
- Rest timer with 90-second and 3-minute quick starts.
- Mobile bottom navigation.
- PWA manifest + service worker for install/offline support.
- Existing monthly leaderboard, weekly consistency XP, banners, and strength-percentile tools retained.

## Data
Workout data is stored in browser localStorage on the device. Export a JSON backup before clearing browser data or moving devices.

## Running
Open `index.html` in a browser. PWA installation/offline caching requires the app to be served from HTTPS or localhost because browsers restrict service workers on `file://`.
