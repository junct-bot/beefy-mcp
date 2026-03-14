# Beefy MCP Server

MCP server for Beefy. Agent-ready API for Beefy.

Hosted at [beefy.mcp.junct.dev/mcp](https://beefy.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "beefy": {
      "url": "https://beefy.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Beefy API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Beefy
- **Endpoint:** `https://beefy.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [beefy.mcp.junct.dev/llms.txt](https://beefy.mcp.junct.dev/llms.txt)
- **Server card:** [beefy.mcp.junct.dev/.well-known/mcp/server.json](https://beefy.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/beefy)
- [llms.txt](https://beefy.mcp.junct.dev/llms.txt)
- [agents.md](https://beefy.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://beefy.mcp.junct.dev/openapi.json)

## Keywords

Beefy, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
