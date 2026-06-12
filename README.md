# MetaVision MCP Server

AI 3D model generation for Claude Desktop and other AI assistants.

## Install

Add to your `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "metavision": {
      "command": "python3",
      "args": ["mcp_server.py"]
    }
  }
}
```

## Tools

- **generate_3d_from_text** - Generate 3D model from text
- **check_3d_status** - Check generation progress  
- **validate_api_key** - Check API credits
- **browse_3d_gallery** - Browse gallery

## Get API Key

https://metavision.click/docs
