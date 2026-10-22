# notes-cli Roadmap

Roadmap for **notes-cli**, a small command-line tool that turns Markdown reading notes into clean HTML pages.

Workstreams are listed as milestones, in priority order (most urgent first). Each milestone is tracked as a sub-issue of the tracking issue ("Notes CLI project plan", #1).

## Milestone 1 — Implement markdown-to-HTML conversion (priority 1)

The core of the tool: parse Markdown reading notes and emit clean, self-contained HTML pages — readable headings, preserved links and emphasis, and no manual cleanup. Also covers handling a single file or a whole notes directory. Tracked in issue #3.

## Milestone 2 — Set up repository scaffolding (priority 2)

Stand up the project structure: repository layout, `pyproject.toml`, module/package skeleton, entry point for the CLI, and basic project conventions. Tracked in issue #2.

## Milestone 3 — Package and publish to PyPI (priority 3)

Make the tool installable: finalize packaging metadata, build distributable artifacts, and publish to PyPI so `notes-cli` can be installed with `pip`. Tracked in issue #4.
