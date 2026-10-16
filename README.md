# Generic Claude Code Project Template

A clean, reusable project template for any future Claude Code, Codex, or AI-assisted workstream.

This template is intentionally generic. It is not tied to finance, Excel, Python, websites, apps, documents, or any specific type of project.

## Use this template when

- Starting a new project with Claude Code.
- Handing work between ChatGPT, Claude, Codex, and a human reviewer.
- You need organized folders, clear requirements, change tracking, and safe handoffs.
- The project may grow over multiple sessions or branches.

## Core files

| File | Purpose |
|---|---|
| `CLAUDE.md` | Standing instructions for Claude Code and other agents |
| `HANDOFF.md` | Current state, next step, blockers, and resume notes |
| `CHANGELOG.md` | Chronological record of meaningful changes |
| `PROJECT_INDEX.md` | Map of what belongs where |
| `README.md` | Human-readable overview |

## Folder layout

```text
.
├── CLAUDE.md
├── HANDOFF.md
├── CHANGELOG.md
├── PROJECT_INDEX.md
├── README.md
├── .gitignore
├── .env.example
├── 00_admin/
├── 01_requirements/
├── 02_design/
├── 03_work/
├── 04_tests/
├── 05_reviews/
├── 06_handoffs/
├── 07_decisions/
├── 08_reference/
├── 09_outputs/
├── 10_archive/
├── assets/
├── config/
├── data/
├── docs/
├── scripts/
├── src/
└── templates/
```

## How to start a new project

1. Copy this template into a new repo.
2. Fill in `01_requirements/PROJECT_BRIEF.md`.
3. Update `HANDOFF.md`.
4. Start Claude Code in the repo root.
5. Use the prompt in `templates/prompts/CLAUDE_CODE_START_PROMPT.md`.

## Template principle

The root folder should tell the next person or AI agent:

- What this project is.
- What state it is in.
- What was changed.
- What should happen next.
- Where every type of file belongs.
