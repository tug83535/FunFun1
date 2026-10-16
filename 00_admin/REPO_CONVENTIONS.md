# REPO_CONVENTIONS.md

## Branch naming

Suggested branch patterns:

| Pattern | Use |
|---|---|
| `main` | stable baseline |
| `agent/<task-name>` | AI-agent work |
| `feature/<task-name>` | feature work |
| `review/<topic>` | review-only work |
| `fix/<issue>` | bug fixes |
| `archive/<name>` | preservation branches |

## Commit messages

Use direct messages:

```text
Add project brief template
Update handoff after initial setup
Create review checklist
```

## File naming

Prefer dated files for logs and session artifacts:

```text
YYYY-MM-DD_topic_name.md
```

For reusable templates, use clear stable names:

```text
PROJECT_BRIEF.md
REVIEW_CHECKLIST.md
HANDOFF_TEMPLATE.md
```
