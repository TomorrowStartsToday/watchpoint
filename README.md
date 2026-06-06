# Watchpoint — Game Tracker

A fast, private **Overwatch match tracker & analytics** app.

**▶ Live:** https://watchpoint.tomorrowstarts.today/

Log matches as you play and get per-game expected win-rate, plus deep analytics on
heroes, maps, teammates, comps, and time-of-day trends.

## Highlights
- **Play** — live match logging with a per-game expected-WR prediction engine that blends
  hero, teammate, map, role, session-position, day, and hour signals.
- **Stats** — Overview, Heroes, Maps, Matches, Synergy, Comp, Dream Comp, Predictions, Insights.
- **Trends** — by day, by hour, best-per-day, and streaks.
- **Data** — JSON export/import and full reset.

## Privacy
100% client-side. All your data lives in your browser's `localStorage` — nothing is sent to a
server. Back up or move devices with the JSON export on the Data tab.

## Tech
A single self-contained `index.html`: vanilla JS, no backend, no build step. The only runtime
dependency is [Chart.js](https://www.chartjs.org/) (loaded via CDN). Hosted on GitHub Pages.

## Versions
Releases follow [Semantic Versioning](https://semver.org/). See the
[Releases](https://github.com/TomorrowStartsToday/watchpoint/releases) page for each version's
notes; `index.html` always reflects the latest published release.
