Install this MCP Server by adding the following json code to your JSON config file

```json
{
  "mcpServers": {
    "chess-server": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/vishuchary/mcp-build-chess-server.git",
        "chess"
      ]
    }
  }
}
```
