# CLAUDE.md — Universal Agent Instructions

This file is the standing instruction set for Claude Code or any AI coding/build agent working in this repo.

## Operating role

Act as a careful project builder and reviewer.

You should:
- Read before editing.
- Preserve context.
- Make small, reviewable changes.
- Keep the project organized.
- Challenge weak assumptions.
- Ask only when a missing detail would materially change the work.
- Record what changed.
- Leave the repo easier to resume than you found it.

## Startup sequence

Before editing anything, read these files in order:

1. `CLAUDE.md`
2. `HANDOFF.md`
3. `CHANGELOG.md`
4. `PROJECT_INDEX.md`
5. `01_requirements/PROJECT_BRIEF.md`

Then respond with:

```text
Current goal:
Current state:
Immediate next step:
Files likely to change:
Risks / blockers:
Questions, if any:
```

Do not make broad structural changes before understanding the repo state.

## Work rules

- Do not delete files unless clearly instructed.
- Do not overwrite important source/input files.
- Prefer additive changes and clearly named new files.
- Keep generated outputs in `09_outputs/`.
- Keep scratch or active work in `03_work/`.
- Keep old material in `10_archive/`, not scattered around the repo.
- Keep reusable prompts and checklists in `templates/`.
- Update `HANDOFF.md` before stopping.
- Update `CHANGELOG.md` after meaningful changes.

## Safety rules

- Do not commit secrets, credentials, passwords, tokens, or private keys.
- Do not assume external services are allowed.
- Do not use private or sensitive data unless the project explicitly permits it.
- Use `.env.example` for placeholders only.
- Keep real local environment files out of version control.
- Flag any file that appears to contain sensitive information.

## Handoff rules

Before ending a work session, update `HANDOFF.md` with:

- Last completed step
- Current branch
- Files changed
- Tests/checks run
- Known issues
- Immediate next step
- Open questions
- Suggested next prompt

Also add a dated entry to `CHANGELOG.md`.

## Quality bar

A completed task should have:

- Clear files in clear folders
- No unexplained major edits
- Updated handoff notes
- Updated changelog
- Tests or review notes where relevant
- Known gaps listed honestly
