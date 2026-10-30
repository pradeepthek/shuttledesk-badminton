# Badminton Tournament Manager

A browser-based organiser for badminton tournaments, built for the **Indo-Swiss Sports Club**.
Run several events at once (men's, women's and mixed doubles, singles, kids), manage the courts, enter results and show live standings to the players on a second screen.

It is a single `index.html` file: no installation, no server and no account needed.

---

## Features

**Events and formats**
- Several events in one tournament, each with its own name, colour, type (singles or doubles), scoring and home courts
- Three formats per event:
  - **Groups, then semi-finals and final** (crossed-over semis: A1 v B2, B1 v A2)
  - **Groups, then Gold, Silver and Bronze brackets** (group ranks decide the bracket)
  - **Round robin only** (one group, the table decides 1st, 2nd and optionally 3rd)
- Optional 3rd place match per bracket
- Scoring per stage: points to win, cap, 1 game or best of 3 (e.g. 15 points in the groups, 21 in the knockout)
- Group tables ranked in BWF order: matches won, head-to-head when two are level, then games and points difference

**On the day**
- Courts panel shared by all events, with a timer per court
- Suggests the next match per court: home-court events first, then shared fairly between events
- Stops a player being put on two courts at once, even across events (players are recognised by name)
- Rest time per player ("rested 14 min", "just finished")
- Walkovers, withdrawals (matches become void) and adding pairs mid-tournament, with automatic re-planning of unplayed matches
- Match times recorded from "on court" to result, with a planning calculator for future tournaments

**For players**
- Player display for a second monitor: one event, or all events rotating every 15 seconds
- Shows standings or brackets, plus On court, Up next and Latest results, and fits any screen size

**Printing and results**
- Score sheets as PDF (A4 landscape, 10 per page, with cutting lines), per group, per event, all events or blank
- Final results as PDF with set scores, trophies and players' full names

**Admin**
- Optional admin password for Setup and Settings
- Backup and restore as a text file: everything, or setup only (no scores) to hand over to a colleague

---

## Getting started

1. Open the site (or open `index.html` in Chrome, Edge, Firefox or Safari).
2. It starts with an **example tournament** so you can try everything.
3. Go to **Setup**:
   - **Tournament & events:** name, number of courts, then add your events and pick their formats.
   - **Entries:** add players or pairs to each group (one per line, partners separated by `&`, e.g. `Arun & Meera`).
   - **Full names** (optional): used only in the final results PDF.
4. Click **Create tournament**.
5. On the **Groups** tab, start matches on free courts and enter results.
6. When the group stage of an event is finished, create its draw on the **Knockout** tab.

Tip: write each player's name the same way in every event, so the site can recognise them across events.

---

## Where the data is stored

- All tournament data is saved **in your own browser** on your device. Nothing is sent to a server.
- Another browser or computer will not see your data. Use **Setup → Backup** to move a tournament: download a backup file and restore it on the other device.
- Clearing the browser's site data deletes the saved tournament and the admin password, so download a backup regularly.
- The player display must run in the **same browser on the same computer** (e.g. a laptop with an extended monitor) to update live.

---

## Requirements

- A current version of Chrome, Edge, Firefox or Safari
- An internet connection for the fonts and for creating PDFs. Scoring itself works offline once the page is open.

---

## Copyright

© 2026 Pradeep Thekkottil. All rights reserved.

This project is **not licensed for reuse**. You may view the code, but you may not copy, modify, distribute or use it, in whole or in part, without written permission from the author.
