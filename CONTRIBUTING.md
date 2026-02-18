# Contributing to studious-disco

This project is meant to be beginner-friendly and easy to collaborate on. Whether you’re fixing a typo, improving the UI, or working on the scheduler, your help is appreciated.

Before contributing, please read our **Code of Conduct** (`CODE_OF_CONDUCT.md`). The short version: be respectful, assume good intent, and keep the discussions constructive.

---

## Ways to contribute

There are a few main ways to help:

### 1) Report bugs
If something is broken or confusing, open a GitHub Issue. A great bug report includes:
- what you expected to happen
- what actually happened
- steps to reproduce
- your environment (OS + browser)
- screenshots or console logs if relevant

### 2) Suggest features / improvements
Feature requests are welcome. When proposing a feature, please include:
- the problem you’re solving (who it helps and why)
- a proposed solution (what it should do)
- alternatives you considered
- any screenshots / mockups if UI-related

### 3) Submit code (pull requests)
Pull requests are the best way to contribute changes. Small, focused PRs are easiest to review and merge for me.

Good contribution areas:
- UI/UX improvements (layout, accessibility, mobile polish)
- Scheduler improvements (new strategies, better balancing)
- Import/export (CSV, JSON, later ICS)
- Documentation improvements (examples, screenshots, clarity)
- Validation and edge cases (dates, hours, “impossible” schedules)

---

## First-time contributors

If you’re unsure what to work on, open an issue describing what you’d like to do and I'll point you to something.

---

## Development setup

### Requirements
- Node.js (LTS recommended)
- npm

### Run locally
```bash
git clone https://github.com/NAU-OSS/studious-disco.git
cd studious-disco
npm install
npm run dev
