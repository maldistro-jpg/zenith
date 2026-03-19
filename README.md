# Zenith

**The highest point — where your goals live.**

Zenith is a personal academic planner built as a single HTML file. No installation, no backend, no internet required after the first load. Just open it and start planning.

---

## What it does

- **Assignments** — Add homework, quizzes, tests, exams, labs, projects, and long-term assignments with priority levels, due dates, progress sliders, and notes
- **Classes** — Set up your classes with custom colors, teacher names, and links. Each class gets its own dedicated page
- **Daily View** — Hour-by-hour calendar for any day
- **Weekly View** — Full 7-day layout with all assignments visible
- **Monthly View** — Big-picture calendar with color-coded assignment pills
- **Dark / Light Mode** — Toggle with one click, preference is saved
- **Offline Storage** — Everything saves to your browser's localStorage. Your data persists between sessions with no account needed

---

## Tech stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, CSS variables) |
| Logic | Vanilla JavaScript (no frameworks) |
| Storage | localStorage (fully offline) |
| Fonts | DM Serif Display, DM Mono, Plus Jakarta Sans via Google Fonts |

---

## File structure

```
zenith/
└── index.html    ← entire app lives here
```

---

## Notes

- No data leaves your device. Everything is stored locally in your browser.
- Clearing your browser's site data will erase your assignments. Export or back up periodically.
- Works best in Chrome or Safari.
