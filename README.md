PaceDeck
A 7-Zone Swim Pacing Calculator for the Pool Deck
Version 1.2.0
---
What this is
PaceDeck turns a single timed test — 200m, 400m, 2000m, or 3000m — into a full set of
training paces across seven color-coded effort zones, from easy aerobic swimming up to
maximum-speed sprinting. Enter one time, and it instantly builds a pace chart for every zone
across seven common training distances (50m–500m).
It's a single, self-contained web page. There's nothing to install, no account to create, and no
internet connection required after you've opened it once — everything runs and saves directly in
your browser.
---
The color-zone system, explained
Many competitive swim coaches use a color-coded shorthand to describe training intensity instead
of (or alongside) percentages and lap times — it's quick to say on deck, easy for swimmers to
remember, and it maps directly onto how hard an effort actually feels. This approach traces back
to a color-coding method popularized by a legendary US collegiate swim coach in the 1990s–2000s,
and it has since been adapted and taught by many coaches across the sport. PaceDeck is
compatible with that classic color-zone approach — it is an independent tool built to work
with the same seven-zone structure, not an official or endorsed product of any individual coach or
program.
The seven zones, from easiest to hardest:
Zone	Category	What it trains
⚪ White	Aerobic Base (EN1)	Easy, low-intensity aerobic swimming — warm-up and recovery pace
🌸 Pink	Aerobic Endurance (EN1)	Sustainable aerobic pace, slightly faster than White
🔴 Red	Anaerobic Threshold (EN2)	"Comfortably hard" — the pace where the body starts producing more lactate than it can clear
🔵 Blue	Aerobic Capacity / VO2 (EN3)	High-end aerobic work — sustained speed just below race pace, building aerobic power
🟣 Purple	Sprint / Race Pace (SP1)	Fast, controlled-effort swimming close to actual race pace
🟢 Green	Lactate / Race Quality (SP2)	Short, hard repeats with generous rest — builds lactate tolerance and top-end speed
🟡 Gold	Max Speed (SP3)	All-out, fully-rested sprints — pure speed and power
Each zone's pace is calculated from your swimmer's test time using zone-specific pace factors, so
a 400m test produces meaningfully different White-zone and Gold-zone paces — not just a flat
percentage of the test time.
A quick word on precision: coaches who've taught and adapted this system over the years don't
all use identical heart-rate cutoffs or zone names — the framework has evolved and been
re-interpreted many times. PaceDeck uses one well-documented, internally consistent version
of the system. If your program uses slightly different HR bands, treat the zone names and order
as the reliable part, and feel free to recalibrate around your own team's testing.
---
How PaceDeck implements it
Calculate tab — enter a swimmer's name, stroke, course, test distance, and test time. Get an
instant, full 7-zone pace breakdown across all standard distances.
Course selector (LCM / SCM / SCY) — tags each result as Long Course Meters, Short Course
Meters, or Short Course Yards, and switches the displayed distance unit (m/y) to match. This is
for tracking and labeling purposes — it does not apply a course-conversion factor between
meters and yards. Enter a test time that was actually swum in that course for accurate paces.
Squad Dashboard — save swimmers to a squad and see the whole team's zone paces in one
sortable, searchable table. Each swimmer can hold paces for multiple stroke-and-course
combinations at once (e.g. Freestyle/LCM and Freestyle/SCY, or Freestyle and Backstroke), and
you can flip between them with a single click — nothing is overwritten unless you confirm it.
Set Builder — build your own custom set (e.g. "4×50 White, 1×200 Red, 2×100 Purple") and
every swimmer's dashboard and TV display updates to show exactly that set.
TV Mode — a full-screen, high-contrast display designed to be shown on a poolside TV or
monitor during practice, so the whole squad can see their own paces for the set at a glance.
Backup & Restore — export your whole squad and set configuration as a JSON file (for backup
or moving to another computer) or a CSV file (for spreadsheets/records).
Print — print or "Save as PDF" any swimmer's individual pace chart.
---
How to use it
Open the file. Double-click `pacedeck.html`, or drag it into any browser
(Chrome, Safari, Edge, Firefox all work). No install, no server, no login.
Calculate a pace. Enter the swimmer's name, pick their stroke and test distance, type in
their test time (`MM:SS.t`, e.g. `8:39.0`, or plain seconds), and click Calculate.
Add them to the squad. Click Add to Squad on the results screen. If you calculate a
different stroke for the same swimmer later, it's added alongside their existing stroke, not
overwritten — you'll be asked before anything is replaced.
Build your set. In the Set Builder, choose which zones and distances you want visible
(e.g. only the distances you're using in tonight's practice) — this updates the dashboard and
TV Mode instantly.
Go to TV Mode. Click the TV Mode button (or press `Ctrl/Cmd + F`) to show a full-screen
squad display. Click Exit or press `Esc` to leave.
Back up your data regularly. Everything is saved locally in your browser only — it is
not synced anywhere. Use Backup (JSON) every so often (e.g. weekly, or before clearing
your browser data) so you never lose your squad. Use Restore to load a backup back in, on
this computer or a new one.
Erasing data. The Erase All Data button permanently clears everything saved in this
browser. There's no undo — always back up first if you're not sure.
---
Data & privacy
PaceDeck stores everything locally in your browser's storage. Nothing is sent to a server,
because there is no server — it's a single HTML file. This means:
Your swimmers' data never leaves your device.
Data is tied to this specific browser on this specific device. Opening the file on a different
computer, or in a different browser, starts with an empty squad until you Restore a backup.
Clearing your browser's site data/cache will erase your saved squad — back up first.
---
Support
This is a self-contained tool with no ongoing subscription or account. If you run into a bug or
have a feature request, keep a note of your version number (shown at the top and bottom of the
app) when you report it.
