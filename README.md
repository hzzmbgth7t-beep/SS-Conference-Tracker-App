# SS Conference Tracker App

The Southern Software conference tracker: five views (Overview, Money, Logistics, Evidence, Lookup) reading the Supabase database after sign-in.

**This repository is PUBLIC. It holds the page only, never data and never secrets.**
- The conference data stays in the database behind sign-in and row-level security.
- `config.js` holds the project address and the *publishable* key, which are meant to be public. The secret key must never be put in this repository.

Files: `index.html` (the whole app in one file), `config.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`.

Version 3.0.0, built 2026-10-02 06:20 ET. To update the app, replace `index.html` with the new one. Keep `config.js` as it is.
