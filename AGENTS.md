@README.md

## Working in this repo

The primary location for new personal commands is `alex_talon/`. Submodules should not be edited directly — changes to forked submodules (`talon_community_fork`, `mouse_guide`, `alex_talon`, `GoogleSheetsTalonCommands`) go in their own repos and are pulled in here via `git submodule update`.

When adding commands for a new app or tool, follow the pattern in `alex_talon/apps/` — a `.py` file for module/tag/list declarations and a `.talon` file for voice commands. Reusable infrastructure (like `alex_talon/slash_commands/`) should be generic and activated by tags so other apps can opt in.
