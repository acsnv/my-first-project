# AGENTS.md

This repo is a lightweight learning playground for Adrian and AI coding agents (Codex CLI) to experiment, prototype, and iterate quickly. Unless a task explicitly says otherwise, agents may create and modify files as needed.

## Scope and expectations

- Purpose: simple web experiments, tiny utilities, and docs.
- Tech: plain HTML/CSS/JS by default; add frameworks only if the task requires it.
- Keep changes minimal, focused, and easy to review.

## Agent guidelines

- You are authorized to create, edit, move, and delete files in this repo.
- Prefer small, single‑purpose commits with clear, imperative messages.
- Avoid adding heavy dependencies unless justified by the task.
- Do not add license headers unless requested.
- Match existing style; keep the structure simple.
- Update or add brief docs when behavior or usage changes.

## HTML/CSS/JS conventions

- For static pages, use a single `index.html` at the root or in a feature folder.
- Keep CSS embedded for tiny demos; extract to `/styles` as complexity grows.
- Keep JS inline for very small scripts; extract to `/scripts` when needed.

## Hosting via GitHub Pages

- Pushes to `main` trigger a GitHub Actions workflow that publishes the site.
- The workflow uploads the repository root as a Pages artifact and deploys it.
- The live URL will be: `https://acsnv.github.io/my-first-project/` once GitHub Pages is active.

## Local preview

- Run: `python3 -m http.server -d . 8000` from the repo root.
- Open: `http://localhost:8000/`

## Directory layout

- `/index.html` — default landing page (Hello Adrian).
- `/.github/workflows/deploy-pages.yml` — Pages deployment workflow.

