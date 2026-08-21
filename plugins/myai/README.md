# myai

Connects Claude Code to [Make Yourself AI](https://makeyourself.ai) over MCP.

Once installed, Claude Code can start a session with your myai agents, send messages to your dimensions, invoke platform tools, and build and publish apps, all from the terminal. Each session is a real myai work order, so context carries across turns.

## Install

```
/plugin marketplace add MakeYourselfAI/claude-plugins
/plugin install myai@myai
```

On first use Claude Code opens a browser window to sign in to myai. Your existing myai login works; there are no API keys to manage.

## Companies with their own myai site

The plugin connects to the myai beta (`api-beta.makeyourself.ai`). If your company runs its own myai site, skip the plugin and add your site's MCP server directly:

```bash
claude mcp add --transport http myai https://api-acme.makeyourself.ai/api/mcp
```

In Claude Desktop or Cowork, add it as a custom connector with the same URL. Sign-in is the same OAuth flow.

## Access

The beta is currently invite-only. If sign-in fails, ask your myai contact for an invite.
