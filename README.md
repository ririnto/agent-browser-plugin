# agent-browser-plugin

Expose the upstream agent-browser MCP server to Claude Code and Codex.
Make Bun available on PATH before loading the plugin.
The [Claude Code](.mcp.json) and [Codex](mcp.json) configurations own the server command and environment.
System certificate authorities support environments with trusted organizational certificates without disabling TLS verification.
Bun respects the package launcher’s Node shebang by default.
For Node.js system CA support, use Node.js 22.19+, 24.6+, or a later supported release.
See the [Bun runtime documentation](https://bun.com/docs/runtime/environment-variables) and [Node.js CLI documentation](https://nodejs.org/api/cli.html#node_use_system_ca1).

Install `agent-browser-plugin@sinon` through the host plugin manager.
See the [upstream documentation](https://github.com/vercel-labs/agent-browser) for browser installation and usage.
