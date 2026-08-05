# Talon User Directory

This repo wires together a set of submodules and local files that make up Alex's Talon voice control configuration.

## Submodules

### Personal

| Directory | Repo | Notes |
|---|---|---|
| `alex_talon` | [alexander-clarke/alex_talon](https://github.com/alexander-clarke/alex_talon) | Personal app, game, and utility commands. The primary place for new custom commands. |
| `talon_community_fork` | [alexander-clarke/community_talon](https://github.com/alexander-clarke/community_talon) | Fork of the community Talon command set on the `alex-personal` branch. Core vocabulary, editing, navigation, terminal, and language tags. |
| `mouse_guide` | [alexander-clarke/mouse_guide](https://github.com/alexander-clarke/mouse_guide) | Fork of a visual mouse guidance overlay. |
| `GoogleSheetsTalonCommands` | [alexander-clarke/GoogleSheetsTalonCommands](https://github.com/alexander-clarke/GoogleSheetsTalonCommands) | Voice commands for Google Sheets (editing, math, movement). |

### Third-party integrations

| Directory | Repo | Notes |
|---|---|---|
| `rango-talon` | [david-tejada/rango-talon](https://github.com/david-tejada/rango-talon) | Talon side of the Rango browser extension — voice-driven link clicking and web interaction. |
| `cursorless-talon` | [cursorless-dev/cursorless-talon](https://github.com/cursorless-dev/cursorless-talon) | Talon side of Cursorless — voice-driven structural code editing in VS Code. |
| `talon_hud` | [chaosparrot/talon_hud](https://github.com/chaosparrot/talon_hud) | Heads-up display overlay showing active modes, command history, and status. |
| `talon-gaze-ocr` | [wolfmanstout/talon-gaze-ocr](https://github.com/wolfmanstout/talon-gaze-ocr) | Eye-tracking + OCR integration for clicking on arbitrary text (`beta` branch). |
| `talon-ai-tools` | [C-Loftus/talon-ai-tools](https://github.com/C-Loftus/talon-ai-tools) | AI-assisted dictation and text transformation commands. |
| `flex-mouse-grid` | [brollin/flex-mouse-grid](https://github.com/brollin/flex-mouse-grid) | Flexible grid overlay for precise mouse positioning. |
| `talon-filetree-commands` | [paul-schaaf/talon-filetree-commands](https://github.com/paul-schaaf/talon-filetree-commands) | Commands for navigating file tree panels in editors. |
| `homophoner-talon` | [BlueDrink9/homophoner-talon](https://github.com/BlueDrink9/homophoner-talon) | Homophones correction — swaps commonly confused words. Overrides in `homophoner_overrides.csv`. |
| `speak-the-spire-talon` | [brollin/speak-the-spire-talon](https://github.com/brollin/speak-the-spire-talon) | Voice control for Slay the Spire. |

## Local directories (not submodules)

| Directory | Notes |
|---|---|
| `clickless_mouse` | Clickless mouse — dwell-to-click and noise-to-click input. |
| `gamepad_tester` | Gamepad input testing tool. |
| `cursorless-settings` | Local Cursorless configuration (custom scope colours, etc.). |

## Loose files

| File | Notes |
|---|---|
| `parrot.talon` / `parrot_integration.py` | Parrot noise recognition integration (pop, hiss, etc.). |
| `homophoner_overrides.csv` | Personal homophone overrides for homophoner-talon. |
