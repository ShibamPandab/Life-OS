# CLAUDE.md

Guidance for Claude Code (or any future session) working in this repository.

## What this repository is

A personal Life Operating System ("Life OS"), implemented from **`Life_OS_Blueprint_v1.pdf`** — an architecture document the user maintains outside this repository. That blueprint is the source of truth. Claude's role is to **implement it incrementally as a software repository, not redesign it**. If a decision isn't already settled by the blueprint, ask the user rather than assume.

### Mission
See [README.md](README.md#mission) for the mission statement (from the blueprint).

### Core principles (from the blueprint)
- Systems > Goals
- Identity > Habits
- Principles > Rules
- Feedback > Perfection
- Leverage > Hard Work
- Compounding > Intensity

### Architecture (from the blueprint)
Kernel, Identity Engine, Decision Engine, Knowledge Engine, Learning Engine, Health Engine, Wealth Engine, Career Engine, Creation Engine, Relationship Engine, Time Engine, Execution Engine, Review Engine, AI Co-Pilot Layer.

### Build order (from the blueprint)
Kernel → Identity → Decision → Time → Execution → Knowledge → Learning → Health → Career → Wealth → Creation → Review.

Note: Relationship Engine and the AI Co-Pilot Layer appear in the Architecture list but not in this Build Order — see the open question in [ROADMAP.md](ROADMAP.md#open-question).

### AI layer (from the blueprint) — division of labor across tools
- **ChatGPT:** Strategy & Systems
- **Claude (this tool):** Implementation & Long-form
- **Gemini:** Research
- **Coding IDE:** Build, Refactor, Debug

### Design rules every module must satisfy (from the blueprint)
Repeatable, Measurable, Automatable, Scalable, Low Maintenance, Resistant to Bad Days.

## Current milestone

Life OS v0.1 — see [ROADMAP.md](ROADMAP.md) for status and next steps.

## Working rules

These rules were set explicitly by the user and should be followed without being repeated each session:

- **Never build everything at once.** Work one module at a time.
- **Wait for explicit approval** before starting a new module, even if the next step seems obvious from the roadmap.
- **Keep modules self-contained.** Each module should be understandable on its own.
- **Avoid duplication.** Don't restate content that already lives in another file — link to it instead.
- **Use Markdown** for all content in this repository.
- **Cross-link liberally.** When a file relates to another, link to it (relative paths).
- **Maintain consistency** in tone, structure, naming, and formatting across the repository.
- **Think like a senior software architect:** favor clarity and long-term coherence over speed.
- **Ask before making architectural decisions.** Anything not already settled by the blueprint goes to the user, not to Claude's judgment.
- **Record progress.** When a module is completed, log it in [CHANGELOG.md](CHANGELOG.md) and update [ROADMAP.md](ROADMAP.md).

## Notes for future sessions

- Before reading this repo as a complete picture of intent, check with the user — the full blueprint is external and this repo only reflects what has been built so far.
- Do not add modules, abstractions, or scaffolding "for later." Build only what the current approved step requires.
