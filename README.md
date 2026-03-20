# AgentConf

**Cross-IDE AI Config Syncer** — Write one config, compile to all AI tool formats.

Developers using Claude Code, Cursor, and GitHub Copilot maintain 3 separate instruction files for the same project. AgentConf bridges them: configure once, export everywhere.

## Supported Formats

| Tool | Output File |
|------|------------|
| Claude Code | `CLAUDE.md` |
| Cursor | `.cursor/rules` |
| GitHub Copilot | `.github/copilot-instructions.md` |

## Features

- Visual config editor — no YAML knowledge required
- Live preview of all output formats simultaneously
- Import/export `agentconf.yaml` for version control
- Download all config files at once
- Presets for React/Next.js, Python/FastAPI, and Rust
- LocalStorage persistence — your config survives refreshes
- FunForrest dark theme

## Usage

Open `index.html` in a browser. Configure your project, then:

- **Copy** any format from the preview panel
- **Download All** to get every config file at once
- **Export YAML** to save your canonical `agentconf.yaml`
- **Import YAML** to restore from a saved config

## The Idea

```
agentconf.yaml → CLAUDE.md
               → .cursor/rules
               → .github/copilot-instructions.md
```

One source of truth. Zero config drift.
