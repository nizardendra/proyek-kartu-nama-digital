# AGENTS.md

## Project
- Single static HTML file (`index.html`) — a digital business card. No build step, no package manager, no framework.

## Commands
- No local commands to run. Open `index.html` directly in a browser for preview.

## CI
- `.github/workflows/ci-testing.yml` — runs on push and PR. Only job (`lint-html`) verifies `index.html` exists via `test -f`. No real linting or type checking.

## Conventions
- PRs follow `.github/PULL_REQUEST_TEMPLATE.md`: check mobile view, CI green, no typos, links work.
- Docs and comments are in Indonesian.
