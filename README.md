# STUDIOUS-DISCO

studious-disco is a local-first web app that turns assignment due dates into a realistic weekly study plan.

Most tools stop at “here are your deadlines.” studious-disco is trying to answer the next question: **what should I work on today, and how much?** You enter assignments with due dates and estimated effort, set how many hours you can realistically study per week (and optionally per day), and the app produces day-by-day work blocks that spread the workload out and highlight when a week is overloaded.

Because it’s local-first, the plan lives in your browser by default. There’s no account required and no setup other than just running the app.

## Contact

You can contact me directly at: cjl525@nau.edu

## Why this exists

I built this because a list of deadlines doesn’t help when you’re juggling multiple classes, work, and unpredictable weeks. The main goal is to make workload visible and actionable. A good plan should be easy to adjust and should clearly show tradeoffs (for example: “if I miss today, what gets pushed, and does next week become impossible?”).

## Features (MVP target)

- Create/edit assignments (course, title, due date, estimated hours, difficulty 1–5)
- Availability settings (hours per week + optional daily cap)
- Generate a weekly plan with per-day work blocks
- Overload warnings when a week/day exceeds your limits
- Lock blocks you’ve manually adjusted so regenerate won’t overwrite them
- Local-first storage (no account required)

## Tech stack

- React + Vite + TypeScript
- Local persistence (localStorage to start)

## Installation

### Requirements
- Node.js (LTS recommended)
- npm (bundled with Node)

### Run locally (development)
```bash
# 1) Clone the repo
git clone https://github.com/NAU-OSS/studious-disco.git
cd studious-disco

# 2) Install dependencies
npm install

# 3) Start the dev server
npm run dev
