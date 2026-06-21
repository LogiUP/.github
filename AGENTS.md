# Agent Instructions

## Global
- Think in English; communicate with the user in Vietnamese.
- This repo controls public organization profile material for GitHub.
- Keep content concise, non-sensitive, and safe for public visibility.
- Follow Git rules in `/Users/lap16773/Documents/Projects/LogiUP/logiup-dev-scripts/docs/GIT_CONVENTIONS.md`.

## Structure
- Public org profile: `profile/README.md`.
- Repo README: `README.md`.

## File-Scoped Commands
| Task | Command |
| --- | --- |
| Search profile text | `rg "LogiUP|repo|team" README.md profile` |
| Preview files | `sed -n '1,200p' profile/README.md` |

## Key Conventions
- Do not mention private infrastructure, secrets, customer data, or internal-only links.
- Keep links current with the active split repos.
- Prefer factual product/org descriptions over marketing filler.

## Commit Attribution
AI commits MUST keep the configured repo author and include:
```text
Co-Authored-By: <agent name> <noreply@example.com>
```
