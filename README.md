# openclaw-workspace

Private workspace for my OpenClaw assistant setup.

## What this repo contains

### Core identity and behavior

- `AGENTS.md` — workspace rules and operating conventions
- `SOUL.md` — assistant personality and tone
- `USER.md` — notes about the human
- `IDENTITY.md` — assistant identity
- `TOOLS.md` — local environment notes
- `HEARTBEAT.md` — heartbeat checklist / quiet-mode behavior

### Skills

Selected reusable skills are tracked under `skills/`.

Notable custom skill:

- `skills/film-literature-companion` — a companion skill for:
  - discussing film and literature
  - recording opinions and judgments
  - doing long-form analytical conversation
  - accumulating aesthetic preferences over time

Also includes a curated set of commonly used skills for:

- GitHub workflows
- browser automation
- research and summarization
- Notion and Obsidian workflows
- writing polish / humanization
- image generation
- YouTube transcript analysis

## Git policy

This repo intentionally tracks:

- core assistant identity/config files
- selected stable skills
- custom skills created for this workspace

This repo intentionally ignores:

- local runtime state in `.openclaw/`
- local registry/cache state in `.clawhub/`
- transient lock files and editor noise

See `.gitignore` for details.

## Current custom focus

The main custom direction right now is building the assistant into a stronger partner for:

- UI / product thinking
- coding collaboration
- film and literature conversation
- long-term taste memory

## Notes

This is a living workspace, not a polished public template.
Changes reflect actual assistant evolution and day-to-day use.
