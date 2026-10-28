# The Callahan Run

A game by Asher Niedzwiedz, built in Godot with Claude Code.

## Getting started

1. Install Godot and Python 3 (and Git for Windows, which provides Bash for the studio hooks).
2. Open Claude Code in **this folder** (the one with `CLAUDE.md` and `project.yaml`), not a subfolder.
3. Run `/start`. It asks where the project is at and routes you to the right workflow:
   - `/brainstorm`: work out the game idea
   - `/setup-engine godot`: configure the project for Godot
   - `/prototype`: get something playable fast

With the `godot` MCP server installed (`claude mcp add --scope user godot -- npx -y @coding-solo/godot-mcp`), Claude can launch the game, read errors and fix them.

## Studio setup

The `.claude/` folder, `CLAUDE.md`, `project.yaml` and the `design/`, `docs/`, `production/` and `studio-tests/` folders come from [Claude Code Game Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) v1.2.0 (MIT): 49 agents and 74 skills organized like a game studio. Its full guide is in [docs/STUDIO-README.md](docs/STUDIO-README.md).
