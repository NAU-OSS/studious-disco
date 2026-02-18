# studious-disco 🎓🕺

studious-disco is a local-first web app that turns your assignment due dates into a realistic weekly study plan.

You enter your classes, deadlines, and estimated effort. Then you set how many hours you can study per week (and optionally per day). The app generates day-by-day “work blocks” so you know what to do today, not just what’s due later.

## Why this exists
I felt like a lot of planners are basically glorified due date lists. This project focuses on **time and workload** so it helps answer questions like:
- “How much should I work on today?”
- “Am I overloaded next week?”
- “If I miss a day, what should I shift?”

## Features (MVP)
- Create/edit assignments (course, title, due date, estimated hours, difficulty 1–5)
- Availability settings (hours/week + optional daily cap)
- Generate a weekly plan with per-day work blocks
- Overload warnings when a week/day exceeds your limits
- Lock blocks you’ve manually adjusted so regenerate won’t overwrite them
- Local-first storage (no account required)

## Tech stack
- React + Vite + TypeScript
- Local persistence (localStorage to start)

## Quickstart (development)
Prereq: Node.js (LTS recommended)

```bash
npm install
npm run dev
