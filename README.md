# interview

Interview preparation monorepo — behavioral, system design, and coding.

## Focus

Three pillars:

- **Behavioral** — STAR prep, competency domains, rehearsal.
- **System design** — architecture examples, patterns, AWS drills, runbooks.
- **Coding** — C++17 CP reference handbook, contest submissions.

## Sections

| Path | Content |
| --- | --- |
| [`src/behavioral/`](src/behavioral/README.md) | Behavioral prep guidance (STAR, domains, rehearsal) for behavioral rounds |
| [`src/system-design/`](src/system-design/README.md) | Architecture examples, patterns, AWS drills, 60-minute runbooks |
| [`src/coding/`](src/coding/README.md) | C++17 CP reference handbook, contest submissions |
| [`docs/ecosystem.md`](docs/ecosystem.md) | Repo → tech map of the whole ecosystem |

## Quick start

```bash
# Lint all markdown
markdownlint '**/*.md' --ignore node_modules

# Check links
lychee '**/*.md' --exclude 'https://linkedin.com'
```
