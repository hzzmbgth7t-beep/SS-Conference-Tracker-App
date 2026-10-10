# SS Conference Tracker App

**Version 3.4.0, built 2026-10-10 13:08 ET**

Open the newest version: https://hzzmbgth7t-beep.github.io/SS-Conference-Tracker-App/?v=3.4.0

The Southern Software conference tracker: four views (Overview, Money, Logistics, Evidence) and a Help page chosen from a menu, reading the Supabase database after sign-in, with a State filter and a My shows button on every view, plus an Admin view for users with the admin permission (the owner also manages users there). Approved devices stay signed in until the next app update; Face ID / passkey sign-in is available.

New in 3.4.0: the app checks for a newer version every five minutes and whenever it comes to the front; when one is live, a yellow bar shows the version and its change note and "Tap to update" loads it. Users (owner only): press and hold a user row, or press Manage, to open a window with the actions stacked vertically — Reset temporary password, Change email address, Set as Inactive / Active, Delete account.

Also in 3.3.1: Overview — Current now limits everything (tiles, Shows by state chart, list, Next up) to the ongoing and upcoming shows and puts the completed shows in a Completed section that starts minimised (expand / collapse); the Shows by state chart starts minimised with an Expand / Collapse button and is not shown with the Board; the Board has its own Collapse / Expand button.

Also in 3.3.0: Overview — the Show and Display toggles sit on one row with a Reset button (back to the page as it opens at sign-in); a Search box under them replaces the Lookup page and searches both years (each match shows its year); a Shows by state bar chart runs left to right with the count at the right — press a state and the chart collapses to that bar with its shows listed below; Display gains Full (every detail of each show on the page). Tiles, chart, list and Next up all reflect the search, the pressed tile and the pressed state.

Also in 3.2.0: Users (owner only) — each account shows Active or Inactive with a Set as Inactive / Set as Active button (inactive accounts cannot sign in and sort to the bottom of the list); each account row also has a Manage button that opens three actions: Reset temporary password (new 14-character password, shown once), Change email address (to another @southernsoftware.com address) and Delete account (after a confirmation). Every action is written to the change log. Needs the v3.2.0 "admin-users" user service deployed in Supabase.

Also in 3.1.1: Money tiles are narrower, three to a row on every screen; every tile on Overview and Money reflects the filters in force (State, My shows, a pressed tile, a pressed state bar); a pressed state bar shows a tick and an "All states" button, and the list heading has a "clear" button.

Also in 3.1.0: Help in the Menu — the User Guide for everyone (getting started, the header, every page, chips and labels, your account) and the Admin Guide for admin-tab accounts (permissions, amounts views, the Admin tab, Users, how data and updates get in, rules).

Also in 3.0.9: the menu button always reads "Menu"; on a phone the Southern Software logo is centred on its own row and the year buttons, State filter and My shows share one row.

Also in 3.0.8: cancelled shows stay in every list and count exactly as before, with a grey "Cancelled" chip wherever the show appears (Board, List, Large, Next up, Money, Logistics, Evidence, Lookup and the detail pop-up).

Also in 3.0.7: on the Money tab every tile can be pressed to limit the list, the state bars limit it to one state, and a Conferences tile (the default) lists the year's shows with their money beside Partnership Spending and Component Spending; a show in that list opens its detail pop-up. Partnerships are never limited by the State filter (they are paid to associations, not to shows).

Also in 3.0.6: My shows (only the conferences you are listed as attending in the workbook); Attendee Notes in the detail box and on Large cards; the Overview opens as a List, the four tiles filter the lists and Next up, an All/Current toggle splits ongoing and upcoming shows from completed ones, and choosing a show on the Board, List or Large view opens its full detail as a pop-up.

**This repository is PUBLIC. It holds the page only, never data and never secrets.**
- The conference data stays in the database behind sign-in and row-level security.
- `config.js` holds the project address and the *publishable* key, which are meant to be public. The secret key must never be put in this repository.

Files: `index.html` (the whole app in one file), `config.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`.

To update the app, replace `index.html` (and this README) with the new ones. Keep `config.js` as it is.
