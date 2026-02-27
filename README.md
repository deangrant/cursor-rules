# cursor-workspace

Reusable [Cursor](https://cursor.com) rules and agent skills for consistent, AI-assisted coding and domain guidance across projects.

## What’s in this repo

| Directory | Purpose |
| --------- | ------- |
| [**rules/**](./rules/) | Rule packs (formatting, style, conventions) — each with a `.cursorrules` file and optional README. |
| [**skills/**](./skills/) | Agent skills (domain knowledge, when-to-use guidance) — each with a `SKILL.md` and optional README/reference. |

- **Rules** shape how the AI formats code, follows conventions, and applies style (e.g. Google Python/TypeScript guides).
- **Skills** give the agent focused domain knowledge so it can help with specific topics (e.g. H3 geospatial indexing) when relevant.

## Quick start

- **Rules**: Copy a rule folder into your project (e.g. `.cursor/rules/` or a `rules/` directory) and enable it in Cursor. See [rules/README.md](./rules/README.md) for the list and usage.
- **Skills**: Place skill folders where Cursor can see them (e.g. `.cursor/skills/` or a linked `skills/` directory). See [skills/README.md](./skills/README.md) for the list and usage.

## Adding content

- **New rule**: Add a folder under `rules/` with a `.cursorrules` file and optional `README.md`, then add an entry to the table in [rules/README.md](./rules/README.md).
- **New skill**: Add a folder under `skills/` with a `SKILL.md` (and optional `README.md`), then add an entry to the table in [skills/README.md](./skills/README.md).
