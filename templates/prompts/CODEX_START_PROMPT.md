# CODEX_START_PROMPT.md

Use this when asking Codex or another coding agent to work from this repo.

```text
You are working in this GitHub repo.

First read:
1. README.md
2. CLAUDE.md
3. HANDOFF.md
4. CHANGELOG.md
5. PROJECT_INDEX.md
6. 01_requirements/PROJECT_BRIEF.md

Your job:
- Follow the immediate next step in HANDOFF.md.
- Keep changes small and reviewable.
- Do not commit secrets or sensitive data.
- Keep files organized according to PROJECT_INDEX.md.
- Update CHANGELOG.md.
- Update HANDOFF.md.

Before editing, explain:
- What you plan to change
- Which files you expect to edit
- What risks or questions exist
```
