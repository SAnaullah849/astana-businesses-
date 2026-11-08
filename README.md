# astana-businesses-
A platform for Astana businesses to provide an online presence.

Mobile review pages:

- `/coffee-boom` → `boom.html`
- `/viva` → `viva.html` — Viva, MEGA Silk Way

Static HTML deployed by Vercel from `main`; routes are defined in `vercel.json`.
Each page follows the browser's primary language (Russian or English) and requests
a spoken review invitation on entry. Browsers may require a tap on the robot to
allow audio playback.
