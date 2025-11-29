Install this MCP server by adding the following JSON code to your JSON config file

```json
{   
    "mcpServer":{
        "ChessMCP": {
            "command": "uvx",
            "args": [
            "--from",
            "git+https://github.com/imouiche/mcp-chess-api.git",
            "mcp-chess"
      ]
    }
  }
}

```