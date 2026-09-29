# Kasim Aslam — Second Brain

A structured knowledge base so Claude (and Kasim) can find the right file fast.

**Status:** populated on 2026-09-28 from five source files (interview transcript, website scrape, pricing page, public teammates list, Day 2 voice homework). Anything marked `[TO FILL]` still needs real information from Kasim; `[UNVERIFIED]` means a fact came from one source only.

## How this works
1. **Raw material** (transcripts, documents, scraped pages) lands in `02_Intake/raw/`.
2. Each item is processed into a clean markdown file and logged in `02_Intake/intake-log.md`.
3. Distilled, trustworthy facts live in `01_Context/` — this is the layer Claude reads first.
4. Everything else (projects, knowledge, decisions, comms) builds on top of the context layer.

## Folder map
| Folder | Purpose |
|---|---|
| `00_Start-Here/` | Index, naming rules, how to use this brain |
| `01_Context/` | Core truth: identity, offer, pricing, team, history, voice, goals |
| `02_Intake/` | Pipeline for mined material: raw -> processed, plus the log |
| `03_Projects/` | One subfolder per active project or initiative |
| `04_Knowledge/` | Frameworks, playbooks, FAQs, research |
| `05_Decisions/` | Decision log (what was decided, why, when) |
| `06_Communications/` | Email templates, scripts, published content |
| `07_Archive/` | Old or superseded material (never delete, move here) |

## Golden rules
- One topic per file. Short, descriptive, kebab-case names.
- Every file starts with the frontmatter block (see `00_Start-Here/file-template.md`).
- If a fact is unverified, mark it `[TO FILL]` or `[UNVERIFIED]` — never guess.
- Update `last_updated` whenever a file changes.
