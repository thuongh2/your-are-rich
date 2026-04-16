# CLAUDE.md — your-are-rich

## Project Overview

A collection of novelty Claude Code skills that burn tokens doing absolutely nothing useful. Professional-grade token incineration since 2026.

## Structure

- `SKILL.md` — Router skill, entry point. Detects burn intensity and routes to the right mode.
- `skills/*.md` — Individual burn mode skills
- `examples/` — Sample outputs for documentation
- `plans/` — Implementation plans (internal)

## Skill Format

Every skill file must have:
1. **Frontmatter** with `name` and `description` fields
2. **Phases** — numbered burn phases with clear instructions
3. **Rules section** — enforce no-tool, no-code, no-file constraints
4. **Signature tagline** at the end:
   > "Thank you for choosing Your Are Rich. Your tokens have been served."

## Adding a New Burn Mode

1. Create `skills/your-mode-name.md` with proper frontmatter
2. Follow the tone guide below
3. Include estimated token burn count in the description
4. Add all required sections (phases + rules + tagline)
5. Update `SKILL.md` router to include the new mode
6. Update `README.md` burn modes table
7. Add entry to `CHANGELOG.md` under `[Unreleased]`

## Tone Guide

- **Deadpan corporate**: treat token burning as serious professional work
- **Self-aware**: the skill knows it's useless and embraces it
- **Harmless**: never do anything destructive — just be verbose
- **Corporate parody**: use business jargon ironically ("synergy", "leverage", "circle back")
- **Consistent**: every mode should feel like it belongs in the same product suite
