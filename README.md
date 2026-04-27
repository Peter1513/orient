# orient

Pre-work skill for coding agents. Clarify intent, search precedents, brainstorm approaches — before writing code.

## Install

### Claude Code

```bash
claude plugin marketplace add github:Peter1513/orient
claude plugin install orient@orient
```

### Codex

```bash
codex plugin install github:Peter1513/orient
```

Or search "orient" in Codex plugin browser.

## Usage

| Command | Behaviour |
|---|---|
| `/orient` | Basic start: `scan:off`, `search:auto` |
| `/orient scan:on` | Scan repo before brainstorming |
| `/orient search:always` | Search precedents every round |
| `/orient search:off` | No web search |

Codex: use `$orient` instead of `/orient`.
