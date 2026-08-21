# myai

Connects Claude Code to [Make Yourself AI](https://makeyourself.ai) over MCP.

Once installed, Claude Code can start a session with your myai agents, send messages to your dimensions, invoke platform tools, and build and publish apps, all from the terminal. Each session is a real myai work order, so context carries across turns.

## Install

```
/plugin marketplace add MakeYourselfAI/claude-plugins
/plugin install myai@myai
```

On first use Claude Code opens a browser window to sign in to myai. Your existing myai login works; there are no API keys to manage.

## Pointing at your company's myai site

The plugin connects to the myai beta (`api-beta.makeyourself.ai`) by default. If your company runs its own myai site, set `MYAI_API_HOST` before starting Claude Code:

```bash
export MYAI_API_HOST=api-acme.makeyourself.ai
```

Or set it once for a project in `.claude/settings.json`:

```json
{ "env": { "MYAI_API_HOST": "api-acme.makeyourself.ai" } }
```

## Access

The beta is currently invite-only. If sign-in fails, ask your myai contact for an invite.
