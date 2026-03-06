# Changelog

## Initial Setup

- Add initial skills: Bases, Obsidian Markdown, JSON Canvas
- Create README.md, LICENSE, plugin info
- Add YAML descriptions for skills

## Skills

- Add defuddle and obsidian-cli skills
- Add skill descriptions to all skills
- Improve skill quality scores across 4 skills
- Align skills with Agent Skills specification and Codex compatibility
- Update SKILL.md with latest Obsidian Bases syntax

## Documentation

- Add instructions about JSON newline escaping to avoid common mistakes
- Add Duration type documentation and fix date formulas in obsidian-bases
- Add OpenCode setup instructions to README
- Update README with `npx skills` installation instructions
- Clarify that Maps is a community plugin, not a core plugin

## Bug Fixes

- Fix Claude Code skill discovery by standardizing `skills/` layout
- Fix type error in skill definition
- Replace backticked `!` to avoid Claude Code bash permission error

## Installation

- Add Codex skill installation script and `.codex/INSTALL.md`
- Add Windows PowerShell install script (`scripts/install-skills-codex.ps1`)
- Fix Codex install script URLs to point to upstream `kepano/obsidian-skills`

## Maintenance

- Update plugin version so it can be updated from the marketplace
- Community contributions:
  - #11: Fix type error and replace backticked `!` to avoid Claude Code bash permission error
  - #17: Fix Claude Code skill discovery by standardizing `skills/` layout
  - #20: Clarify that Maps is a community plugin, not a core plugin
  - #27: Align skills with Agent Skills specification and Codex compatibility
  - #32: Add JSON newline escaping instructions to avoid common mistakes
  - #35: Add Duration type documentation and fix date formulas in obsidian-bases
  - #37: Update README with `npx skills` installation instructions
  - #41: Add OpenCode setup instructions to README
  - #43: Update plugin version for marketplace compatibility
  - #44: Improve skill quality scores across 4 skills
