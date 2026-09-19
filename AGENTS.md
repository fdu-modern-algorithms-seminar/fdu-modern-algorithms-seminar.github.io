# AGENTS.md — fdu-modern-algorithms-seminar.github.io

## Commit messages (required)

Follow Conventional Commits, consistent with existing history
(`feat: add simple homepage`, `docs: add initial README ...`):

- Format: `<type>: <short description>`
- `type`: `feat` (new content, e.g. syllabus items, slides),
  `docs` (README / text documentation),
  `fix` (corrections to published content),
  `chore` (build config, `.gitignore`, housekeeping).
- All lowercase, English, concise, imperative mood, no trailing period.
- One logical change per commit; do not bundle unrelated changes.
- Examples:
  - `feat: update first syllabus item to opening lecture title`
  - `docs: add initial README for Modern Algorithms Seminar`

## What to track

- Tracked: `index.html`, `README.md`, `AGENTS.md`.
- Slide sources (`.tex`) and PDFs: only when explicitly requested.
- Never commit LaTeX build artifacts
  (`*.aux`, `*.log`, `*.nav`, `*.out`, `*.snm`, `*.toc`,
  `*.synctex.gz`, `*.fls`, `*.fdb_latexmk`).

## Git safety

- Never commit, push, or force-push without an explicit request.
- Before committing, inspect `git status`, `git diff`, and recent log;
  stage only intended files.
