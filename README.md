# MCP Build Chess Server

Install this MCP server by adding the following JSON code to your config file

```json
{
	"mcpServers": {
		"chess": {
			"command": "uvx",
			"args": [
        "--from",
        "git+https://github.com/JairAviles/mcp-build-chess-server.git",
        "chess"
      ]
		}
	}
}

````