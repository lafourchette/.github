## Cursor Cloud specific instructions

This is a **GitHub Community Health Files repository** (`.github` repo) for the TheFork organization. It contains only Markdown templates that GitHub applies as organization-wide defaults to repositories that don't define their own.

### Repository contents

| File | Purpose |
|------|---------|
| `README.md` | Repository description |
| `CODEOWNERS` | Default code owners (`@lafourchette/thefork-architecture-team`) |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default PR template for all org repos |
| `.github/ISSUE_TEMPLATE/bug.md` | Bug report issue template |
| `.github/ISSUE_TEMPLATE/feature.md` | Feature proposal issue template |
| `.github/ISSUE_TEMPLATE/doc.md` | Documentation issue template |

### Development notes

- **No build system, dependencies, or services.** There is nothing to install, build, or run.
- **Lint:** `markdownlint-cli2 '**/*.md'` — validates Markdown syntax across all files. Pre-existing warnings (line-length, heading-level) are expected.
- **Testing:** No automated tests exist. Validation is limited to markdown linting and manual review.
- Changes here affect all TheFork organization repositories that do not override these templates.
