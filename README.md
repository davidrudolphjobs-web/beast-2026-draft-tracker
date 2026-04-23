# The Beast 2026 — Draft Tracker

A lightweight, single-page NFL Draft tracker built around Dane Brugler's **Top 100** prospects from *The Beast 2026*.

## What it does

- Browse all 100 top prospects, color-coded by position
- Click any name → opens that player's profile on The Athletic in a new tab
- Fill in **Team** and **Pick #** as the draft happens — drafted players strike through
- Filter by position tab or "Hide drafted" to shrink the board as picks come in
- Picks auto-save to the browser's local storage
- Save / Restore JSON backups between draft days (subscription-free portability)
- Dark and light themes

## How to use

Just open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge). Everything runs client-side — no server required.

### Persistence

Picks are saved to the browser's `localStorage`, which persists across sessions on the same browser/device. For real durability across the 3 draft days, use the **💾 Save backup** button to download a JSON file at the end of each day. The **📂 Restore** button lets you import it back if needed.

## Files

- `index.html` — redirect into the app (also the GitHub Pages entry point)
- `claude_artifact_draft_tracker.html` — the app itself (single file, ~55 KB)

## Credits

- Rankings, profiles, headshots and taglines by **Dane Brugler** for **The Athletic** (*The Beast 2026*).
- This is a personal draft-day tool — not affiliated with The Athletic or the NFL.
