# 📖 The Reading Planner

A single-page web app that helps students plan their reading around real deadlines. Measure your actual reading speed with a timed test, tell it what you have to read, and get a day-by-day schedule that fits your due date.

**No install, no accounts, no build step** — it's one self-contained HTML file, and everything you enter stays on your own device.

## Features

- **Reading speed test** — Read a short passage at your natural pace, answer a quick comprehension check, and get your true words-per-minute (so the estimate reflects how *you* read, not a generic average).
- **Books or articles** — Plan a book by page count or page range, or paste in an article (or any text) to estimate it directly.
- **Difficulty adjustment** — Auto-detects how dense pasted text is and slows the estimate for harder material; manual Easy → Technical control for books.
- **Day-by-day schedule** — Set a due date and it splits the reading into dated daily chunks with page ranges and time targets. Print or save it as a study sheet.
- **Flexible planning** — Work backward from a deadline, or forward from "I can read X minutes a day."
- **Copy-as-badge** — Grab a `📖 4 min read` badge for your own posts or notes.
- **Themes & customization** — 8 themes plus custom colors and fonts, all saved automatically between visits.
- **Remembers your speed** — Take the test once; returning visits let you skip straight to planning.

## How to use

1. Open the site.
2. **Step 1:** Take the timed reading test (or enter your speed manually).
3. **Step 2:** Enter your book and how many pages you need to read — or paste an article.
4. **Step 3:** Set your due date to get a daily reading schedule.

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single `index.html`. No frameworks, no dependencies. Settings persist via the browser's local storage.

## Notes

- Words-per-page is an estimate by book type; use the "measure my page exactly" helper for accuracy.
- Fetching an article by URL is best-effort — browsers block reading most other sites for security, so pasting the text is the reliable path.
- Auto-difficulty is a lightweight heuristic (sentence length + long-word density), not a formal readability score.

---

Made for students who'd rather plan their reading than panic about it.
