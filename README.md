# .claude

My Claude Code user config, versioned.

- `CLAUDE.md` — global instructions for all projects (Cursor CLI reads the same file via a `~/AGENTS.md` symlink)
- `settings.json` — permissions, model, harness flags
- `plugins/installed_plugins.json` — plugin manifest
- `.gitignore` — whitelist: everything else in `~/.claude` (transcripts, caches, credentials) stays untracked

Versions of `CLAUDE.md` predating the repo were recovered from Claude Code's `file-history/` snapshots and committed with backdated timestamps, one per day.
