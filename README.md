# SS Conference Tracker App

**Version 3.0.8, built 2026-10-09 17:08 ET**

Open the newest version: https://hzzmbgth7t-beep.github.io/SS-Conference-Tracker-App/?v=3.0.8

The Southern Software conference tracker: five views (Overview, Money, Logistics, Evidence, Lookup) chosen from a menu, reading the Supabase database after sign-in, with a State filter and a My shows button on every view, plus an Admin view for users with the admin permission (the owner also manages users there). Approved devices stay signed in until the next app update; Face ID / passkey sign-in is available.

New in 3.0.8: cancelled shows stay in every list and count exactly as before, with a grey "Cancelled" chip wherever the show appears (Board, List, Large, Next up, Money, Logistics, Evidence, Lookup and the detail pop-up).

Also in 3.0.7: on the Money tab every tile can be pressed to limit the list, the state bars limit it to one state, and a Conferences tile (the default) lists the year's shows with their money beside Partnership Spending and Component Spending; a show in that list opens its detail pop-up. Partnerships are never limited by the State filter (they are paid to associations, not to shows).

Also in 3.0.6: My shows (only the conferences you are listed as attending in the workbook); Attendee Notes in the detail box and on Large cards; the Overview opens as a List, the four tiles filter the lists and Next up, an All/Current toggle splits ongoing and upcoming shows from completed ones, and choosing a show on the Board, List or Large view opens its full detail as a pop-up.

**This repository is PUBLIC. It holds the page only, never data and never secrets.**
- The conference data stays in the database behind sign-in and row-level security.
- `config.js` holds the project address and the *publishable* key, which are meant to be public. The secret key must never be put in this repository.

Files: `index.html` (the whole app in one file), `config.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`.

To update the app, replace `index.html` (and this README) with the new ones. Keep `config.js` as it is.
