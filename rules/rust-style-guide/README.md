# Rust style guide

A Cursor rule pack that enforces consistent Rust formatting and style (line length, file size, rustfmt alignment, comments, naming, and API guidelines).

## Contents

| File | Purpose |
|------|--------|
| **rust-style-guide.mdc** | The Cursor rule — copy into `.cursor/rules/` in your project. |
| **reference.md** | Links to official style guides and checklists (Rust, API guidelines, Microsoft, rustfmt). |

## Usage

1. Copy this folder into your project, or copy **rust-style-guide.mdc** into `.cursor/rules/`.
2. The rule applies when editing `**/*.rs` files (and is set to always apply in the frontmatter).
3. For full context, the rule references **reference.md**; keep that file next to the rule or adjust the path in the rule if needed.

## What it enforces

- **Formatting**: 100-char line length, 500-line file limit, 4-space indent, rustfmt-compatible style.
- **Comments & docs**: Line comments, doc comment placement, canonical sections.
- **Style**: Small functions, early returns, naming conventions, `Debug`/`Display` for public types, panic vs `Result`.
- **References**: Rust style guide, Rust API guidelines, Microsoft Pragmatic Rust, rustfmt.
