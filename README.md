# agent-browser-plugin

Expose the upstream agent-browser MCP server to Claude Code and Codex.
The server runs `bunx agent-browser mcp` over stdio and requires Bun on PATH.
Both host configurations set `NODE_USE_SYSTEM_CA=1` so supported Bun and Node.js runtimes include the operating system certificate authorities while retaining TLS certificate verification.
Bun respects the package launcher’s Node shebang by default.
For Node.js system CA support, use Node.js 22.19+, 24.6+, or a later supported release.
See the [Bun runtime documentation](https://bun.com/docs/runtime/environment-variables) and [Node.js CLI documentation](https://nodejs.org/api/cli.html#node_use_system_ca1).

Install `agent-browser-plugin@sinon` through the host plugin manager.
See the [upstream documentation](https://github.com/vercel-labs/agent-browser) for browser installation and usage.
