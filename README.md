# Instantboard for Cursor

![Instantboard](plugins/instantboard/logo.svg)

Remote [MCP](https://modelcontextprotocol.io) server for [Instantboard](https://instantboard.app) — manage cards and columns from Cursor.

Cursor imports this repository as a marketplace. The plugin lives in `plugins/instantboard`.

## Install

1. Find **Instantboard** on [cursor.directory](https://cursor.directory) and click **Add to Cursor**, or add the config below to `~/.cursor/mcp.json` / `.cursor/mcp.json`.
2. Complete Instantboard OAuth when Cursor prompts you.

```json
{
  "mcpServers": {
    "instantboard": {
      "url": "https://instantboard.app/mcp"
    }
  }
}
```

Server URL: `https://instantboard.app/mcp`

## License

MIT
