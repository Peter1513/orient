# orient

Pre-work skill for coding agents. Clarify intent, search precedents, brainstorm approaches before writing code.

## Install

### Claude Code

Add the marketplace, then install the plugin:

```bash
claude plugin marketplace add Peter1513/orient
claude plugin install orient@orient
```

### Codex

Add the marketplace, then open the plugin browser and install `orient` from the `Orient` marketplace:

```bash
codex plugin marketplace add Peter1513/orient
codex
/plugins
```

## Usage

| Command | Behaviour |
|---|---|
| `/orient:orient` | Basic start: `scan:off`, `search:auto` |
| `/orient:orient scan:on` | Scan repo before brainstorming |
| `/orient:orient search:always` | Search precedents every round |
| `/orient:orient search:off` | No web search |

Codex: use `$orient` or invoke the installed `orient` skill from the plugin browser.

## License

MIT
