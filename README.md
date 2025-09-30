# Hello, MCP Server

## How to run

```
uv sync
source .venv/bin/activate

uvicorn server:app --reload --timeout-graceful-shutdown 0
npx -y @modelcontextprotocol/inspector
```
