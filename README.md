# problem-solving

Interview preparation for the problem-solving side — behavioral stories and a C++17 competitive-programming reference.

## Focus

Two pillars:

- **Behavioral** — work stories + reference prep guidance.
- **Coding** — C++17 CP reference handbook, contest submissions.

System design lives in its own repo: [`system-design`](https://github.com/<OWNER>/system-design).

## Sections

| Path | Content |
| --- | --- |
| [`src/behavioral/`](src/behavioral/README.md) | Work stories + [`reference/`](src/behavioral/reference/README.md) prep guidance for behavioral rounds |
| [`src/coding/`](src/coding/README.md) | C++17 CP reference handbook, contest submissions |
| [`docs/ecosystem.md`](docs/ecosystem.md) | Repo → tech map of the whole ecosystem |

## Quick start

```bash
# Lint all markdown
markdownlint '**/*.md' --ignore node_modules

# Check links
lychee '**/*.md' --exclude 'https://linkedin.com'
```
