# <Project name> — agent instructions

<!-- Keep this file under ~150 lines. Inclusion test, per line: would removing it cause an agent error?
     CLAUDE.md is exactly `@AGENTS.md`; host-specific settings live in .claude/ and .codex/. -->

## 1. Purpose

<One paragraph: what this repository is for.>

Vision: [docs/vision.md](docs/vision.md)

## 2. Commands

Exact commands; "full suite = CI".

| Purpose | Command |
|---|---|
| bootstrap | `scripts/setup` |
| verify | <command> |
| test — single | <command> |
| test — full suite | <command> |
| test — e2e | <command, or "none"> |
| lint | <command> |
| typecheck | <command> |
| smoke | <command> — expected: <result> |

## 3. Structure map

Architecture: [docs/architecture.md](docs/architecture.md)

- `<dir>/` — <what lives there>

Generated and vendored trees (never edit by hand): <paths, or "none">

## 4. Non-obvious conventions + Footguns

- <a rule an agent would get wrong without being told>

## 5. Boundaries

- **Always:** <…>
- **Ask:** <…>
- **Never:** merge your own pull request; <…>

## 6. Tracker and PR workflow

- Tracker: <where work items live>; one work-item shape (What, Done when, spec/context reference,
  Out of scope).
- Pull requests use the repository template; a human merges.

## 7. Router

| Task | Go to |
|---|---|
| verify a change | `.agents/skills/verify/SKILL.md` |
| <task> | <skill or document> |
padding line 1 — measurement of the AGENTS.md size budget
padding line 2 — measurement of the AGENTS.md size budget
padding line 3 — measurement of the AGENTS.md size budget
padding line 4 — measurement of the AGENTS.md size budget
padding line 5 — measurement of the AGENTS.md size budget
padding line 6 — measurement of the AGENTS.md size budget
padding line 7 — measurement of the AGENTS.md size budget
padding line 8 — measurement of the AGENTS.md size budget
padding line 9 — measurement of the AGENTS.md size budget
padding line 10 — measurement of the AGENTS.md size budget
padding line 11 — measurement of the AGENTS.md size budget
padding line 12 — measurement of the AGENTS.md size budget
padding line 13 — measurement of the AGENTS.md size budget
padding line 14 — measurement of the AGENTS.md size budget
padding line 15 — measurement of the AGENTS.md size budget
padding line 16 — measurement of the AGENTS.md size budget
padding line 17 — measurement of the AGENTS.md size budget
padding line 18 — measurement of the AGENTS.md size budget
padding line 19 — measurement of the AGENTS.md size budget
padding line 20 — measurement of the AGENTS.md size budget
padding line 21 — measurement of the AGENTS.md size budget
padding line 22 — measurement of the AGENTS.md size budget
padding line 23 — measurement of the AGENTS.md size budget
padding line 24 — measurement of the AGENTS.md size budget
padding line 25 — measurement of the AGENTS.md size budget
padding line 26 — measurement of the AGENTS.md size budget
padding line 27 — measurement of the AGENTS.md size budget
padding line 28 — measurement of the AGENTS.md size budget
padding line 29 — measurement of the AGENTS.md size budget
padding line 30 — measurement of the AGENTS.md size budget
padding line 31 — measurement of the AGENTS.md size budget
padding line 32 — measurement of the AGENTS.md size budget
padding line 33 — measurement of the AGENTS.md size budget
padding line 34 — measurement of the AGENTS.md size budget
padding line 35 — measurement of the AGENTS.md size budget
padding line 36 — measurement of the AGENTS.md size budget
padding line 37 — measurement of the AGENTS.md size budget
padding line 38 — measurement of the AGENTS.md size budget
padding line 39 — measurement of the AGENTS.md size budget
padding line 40 — measurement of the AGENTS.md size budget
padding line 41 — measurement of the AGENTS.md size budget
padding line 42 — measurement of the AGENTS.md size budget
padding line 43 — measurement of the AGENTS.md size budget
padding line 44 — measurement of the AGENTS.md size budget
padding line 45 — measurement of the AGENTS.md size budget
padding line 46 — measurement of the AGENTS.md size budget
padding line 47 — measurement of the AGENTS.md size budget
padding line 48 — measurement of the AGENTS.md size budget
padding line 49 — measurement of the AGENTS.md size budget
padding line 50 — measurement of the AGENTS.md size budget
padding line 51 — measurement of the AGENTS.md size budget
padding line 52 — measurement of the AGENTS.md size budget
padding line 53 — measurement of the AGENTS.md size budget
padding line 54 — measurement of the AGENTS.md size budget
padding line 55 — measurement of the AGENTS.md size budget
padding line 56 — measurement of the AGENTS.md size budget
padding line 57 — measurement of the AGENTS.md size budget
padding line 58 — measurement of the AGENTS.md size budget
padding line 59 — measurement of the AGENTS.md size budget
padding line 60 — measurement of the AGENTS.md size budget
padding line 61 — measurement of the AGENTS.md size budget
padding line 62 — measurement of the AGENTS.md size budget
padding line 63 — measurement of the AGENTS.md size budget
padding line 64 — measurement of the AGENTS.md size budget
padding line 65 — measurement of the AGENTS.md size budget
padding line 66 — measurement of the AGENTS.md size budget
padding line 67 — measurement of the AGENTS.md size budget
padding line 68 — measurement of the AGENTS.md size budget
padding line 69 — measurement of the AGENTS.md size budget
padding line 70 — measurement of the AGENTS.md size budget
padding line 71 — measurement of the AGENTS.md size budget
padding line 72 — measurement of the AGENTS.md size budget
padding line 73 — measurement of the AGENTS.md size budget
padding line 74 — measurement of the AGENTS.md size budget
padding line 75 — measurement of the AGENTS.md size budget
padding line 76 — measurement of the AGENTS.md size budget
padding line 77 — measurement of the AGENTS.md size budget
padding line 78 — measurement of the AGENTS.md size budget
padding line 79 — measurement of the AGENTS.md size budget
padding line 80 — measurement of the AGENTS.md size budget
padding line 81 — measurement of the AGENTS.md size budget
padding line 82 — measurement of the AGENTS.md size budget
padding line 83 — measurement of the AGENTS.md size budget
padding line 84 — measurement of the AGENTS.md size budget
padding line 85 — measurement of the AGENTS.md size budget
padding line 86 — measurement of the AGENTS.md size budget
padding line 87 — measurement of the AGENTS.md size budget
padding line 88 — measurement of the AGENTS.md size budget
padding line 89 — measurement of the AGENTS.md size budget
padding line 90 — measurement of the AGENTS.md size budget
padding line 91 — measurement of the AGENTS.md size budget
padding line 92 — measurement of the AGENTS.md size budget
padding line 93 — measurement of the AGENTS.md size budget
padding line 94 — measurement of the AGENTS.md size budget
padding line 95 — measurement of the AGENTS.md size budget
