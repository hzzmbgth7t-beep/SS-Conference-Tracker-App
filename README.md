# SS Conference Tracker App

**Version 3.0.5, built 2026-10-08 22:09 ET**

Open the newest version: https://hzzmbgth7t-beep.github.io/SS-Conference-Tracker-App/?v=3.0.5

The Southern Software conference tracker: five views (Overview, Money, Logistics, Evidence, Lookup) chosen from a menu, reading the Supabase database after sign-in, with a State filter on every view, plus an Admin view for users with the admin permission (the owner also manages users there). Approved devices stay signed in until the next app update; Face ID / passkey sign-in is available.

**This repository is PUBLIC. It holds the page only, never data and never secrets.**
- The conference data stays in the database behind sign-in and row-level security.
- `config.js` holds the project address and the *publishable* key, which are meant to be public. The secret key must never be put in this repository.

Files: `index.html` (the whole app in one file), `config.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`.

To update the app, replace `index.html` (and this README) with the new ones. Keep `config.js` as it is.
