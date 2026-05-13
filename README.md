# TaxBuddy Sprint Dashboard

A self-contained sprint planning dashboard for the TaxBuddy product team — Q2 2026 roadmap (April → June).

**Live demo:** https://YOUR-USERNAME.github.io/taxbuddy-sprint-dashboard

---

## Features

- 30 pre-loaded tasks from the Q2 2026 product roadmap
- Add / edit / delete tasks with a full form
- Status tracking: Planned, In Progress, POC, Awaiting Approval, On Hold, Done
- **Retro flag** — toggle any task into the sprint retrospective board
- **Release estimate** with color-coded overdue / due-soon / on-track pills
- **Story points** — inline editable
- **Sprint selector** — filter tasks and stats per sprint
- **Kanban board view** by status
- **Retro board** — Went Well / Needs Improvement / Action Items + velocity chart
- Search, filter by status / priority / owner
- Export filtered tasks as CSV
- **localStorage persistence** — all changes survive page refresh, no backend needed

## Sections

| Section | Owner |
|---|---|
| AI & Conversational Journeys | Gitanjali |
| ChatBuddy Enhancements | Gitanjali |
| Partner Integrations | Pratik / Gitanjali |
| Utility & Back Office | Gitanjali |
| Product Parser Roadmap | Tushar |

## Deploy

This is a single `index.html` file. No build step, no dependencies.

**GitHub Pages:**
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
3. Your dashboard is live at `https://YOUR-USERNAME.github.io/REPO-NAME`

## Local use

Just open `index.html` in any browser. All data is stored in `localStorage`.
