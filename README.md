## Installation Steps

To deploy the add_tool `mcp-server` using Git, run the following command:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/AineshGupta/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```