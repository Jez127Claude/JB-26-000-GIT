# JB-26-000-GIT

## Project Overview
A Git learning and tool setup project. This is the first repository in the JB numbering system, created to learn Git, VS Code, Replit, and Claude Code workflows.

## Project Layout
- `index.html` — Simple static landing page displaying project info
- `README.md` — Basic project identification
- `PROJECT.md` — Full project metadata (name, status, description, tools)
- `hello.txt` — Practice file for Git operations
- `.replit` — Replit environment configuration (Nix stable-25_05)
- `.gitignore` — Ignores `.claude/`

## Tech Stack
- **Type:** Static HTML site
- **Languages:** HTML, CSS (inline)
- **Runtime:** Python 3 built-in HTTP server (dev), static deployment (prod)
- **Environment:** Nix (stable-25_05)

## Running Locally
The workflow `Start application` runs:
```
python3 -m http.server 5000 --bind 0.0.0.0
```
It serves the project root on port 5000.

## Deployment
Configured as a **static** deployment serving the project root directory.
