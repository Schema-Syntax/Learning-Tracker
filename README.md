# Learning Tracker

A personal learning management system for tracking courses, certifications, and professional development across platforms — built as a single, self-contained HTML file.

**[Live Demo →](https://yourusername.github.io/learning-tracker)**

---

## Why I Built This

Every learning platform has a way to save content, but none of them let you organize, filter, sort, or prioritize across platforms in a single unified view. This tool solves that: one place for everything, with the controls that actually matter.

## Features

- Add courses with URL, title, platform, category, status, duration, dates, certificate/badge tracking, and notes
- Filter by status, platform, and category — independently or combined
- Search across titles and notes
- Sort by manual order, status weight, date added/started/completed, title, or platform
- Click any status badge to cycle through statuses — dates auto-fill on start and completion
- Drag to reorder manually
- **Momentum metric** — weighted progress score across all tracked courses (Not Started=0, Paused=1, In Progress=2, Completed=3)
- Manage platforms and categories via Settings panel
- Data lives in a local JSON file — portable, private, and yours

## File-Based Storage

Data is stored in a local `.json` file rather than a database or cloud service — keeping it portable, private, and fully under your control. Put the file in a sync folder (iCloud, Proton Drive, etc.) and access it from any computer running the app.

**Chrome / Edge** — uses the File System Access API for seamless auto-save. Every change writes back to the open file silently.

**Firefox / Safari** — uses import/export mode. Open a file to load data; use the Export button to save changes when done.

Same JSON format either way — fully portable between browsers and machines.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies, no server. Open in any browser.

## Structure

```
learning-tracker/
└── index.html    — the entire app, self-contained
```

---

*Built with AI-assisted development — designed, specified, and iterated from requirements to working tool.*
