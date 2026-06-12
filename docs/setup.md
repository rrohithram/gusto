# Setup Guide — Gusto Meets

## Prerequisites
- A code editor (e.g., VS Code)
- A modern web browser (Chrome/Edge/Firefox)
- Git installed (or use GitHub web UI)

## Getting the project
1. Clone the repository:
git clone https://github.com/rrohithram/gusto.git

2. Open the folder in your code editor.

## Running locally
Since this is plain HTML/CSS/JS, simply open `index.html` in your browser.
(Optional: use the "Live Server" extension in VS Code for auto-reload.)

## Git Workflow & Branching Rules
- **Never commit directly to `main`.**
- Each member works on their own feature branch:
  | Branch                   | Owner   |
  |--------------------------|---------|
  | `feature/landing-page`   | Rohith  |
  | `feature/venue-discovery`| Kanaiya |
  | `feature/auth-pages`     | Aditya  |
  | `feature/docs`           | Koushik |
- Pull the latest changes from `main` before starting new work.
- Make small, incremental commits with clear messages.
- Do not modify files owned by another team member.

## Pull Request Process
1. Push your branch.
2. Open a Pull Request (PR) into `main`.
3. Add a clear title/description of changes.
4. Request review from at least one teammate.
5. Address review comments before merging.
6. Merge only after approval.
