# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2026-04-16

### Added
- **Autopilot Mode** (`your-are-rich-autopilot`) — infinite burn that never stops
  - 4 pre-written seasons with 5 phases each (Origin Story, Literary, Multiverse, Deep Cuts)
  - Procedural season generator for Season 5+ with 14 rotating themes
  - Banned all stopping mechanisms: no conclusions, no tagline, no summaries
  - Only stops when output token limit is physically reached

### Changed
- **ALL MODES**: Added explicit word/paragraph minimums to prevent Claude from being concise
- **ALL MODES**: Added anti-shortcut rules (no bullet points where prose required, no summarizing)
- **Standard Burn** — expanded from 7 to 9 phases (~4-6k tokens, up from ~2-3k)
  - Added Phase 6: Token Therapy Session (therapist dialogue)
  - Added Phase 8: Peer Review (fake academic review of the burn)
  - Added word minimums per phase and 5-sentence paragraph minimums
- **Lite Burn** — expanded from 4 to 6 phases (~1.5-2k tokens, up from ~500-800)
  - Added Phase 4: Lite Horoscope
  - Added Phase 5: Haiku Trilogy with literary analysis
  - Added 4-sentence paragraph minimums and 1,000-word floor
- **Ultra Burn** — expanded from 12 to 15 phases (~15-20k tokens, up from ~6-10k)
  - Added Phase 11: Group Therapy Session
  - Added Phase 12: Fake Academic Paper
  - Added Phase 13: Sequel Teaser
  - Expanded all existing phases with sub-requirements and word floors
  - Added 8,000-word minimum enforcement and 6-sentence paragraph minimums
- **Fortune Cookie** — expanded from 4 to 6 phases (~3-5k tokens, up from ~1.5-2.5k)
  - Added Phase 4: Fortune Debate (fortunes argue about which is more useless)
  - Added Phase 5: Fortune Horoscope (12 food-based zodiac signs)
  - Expanded backstories with mandatory per-number explanations and compatibility
  - Expanded critic review to 600-word minimum with wine pairings

## [1.0.0] - 2026-04-16

### Added
- Initial release of the world's most professional token incinerator
- **Standard Burn** (`your-are-rich`) — 7-phase full combustion protocol (~2-3k tokens)
- **Lite Burn** (`your-are-rich-lite`) — budget-friendly token waste (~500-800 tokens)
- **Ultra Burn** (`your-are-rich-ultra`) — nuclear devastation mode (~6-10k tokens)
- **Fortune Cookie** (`your-are-rich-fortune`) — useless wisdom generator (~1.5-2.5k tokens)
- Router `SKILL.md` with auto-detection of burn intensity
- Professional README with ASCII art logo
- MIT License (free as in freedom, expensive as in tokens)
- Contributing guide for new burn modes
- GitHub Actions CI for burn validation
- Issue and PR templates
- This CHANGELOG (meta-token-burn)
