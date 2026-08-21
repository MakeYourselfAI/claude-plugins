# Make Yourself AI plugins for Claude Code

Official Claude Code plugin marketplace for [Make Yourself AI](https://makeyourself.ai).

```
/plugin marketplace add MakeYourselfAI/claude-plugins
/plugin install myai@myai
```

| Plugin | What it does |
|---|---|
| [`myai`](plugins/myai) | MCP server. Talk to your myai agents, dimensions, and apps from Claude Code. |

## Layout

```
.claude-plugin/marketplace.json   catalog
plugins/<name>/                   one directory per plugin
```

## Development

```
claude plugin validate .
/plugin marketplace add ./claude-plugins
```
