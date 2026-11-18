# Agent Browser MCP

Automate a browser through the upstream [Agent Browser](https://github.com/vercel-labs/agent-browser) MCP server.

## Runtime

Install Bun with `bunx` on PATH and Node.js 22.19+ on 22.x or 24.6+ on 24.x, or a newer supported major. The plugin runs `bunx agent-browser mcp` with system certificate support.
Follow the [upstream browser setup](https://github.com/vercel-labs/agent-browser#installation) before opening your first page.

## Install

### Claude Code

```sh
claude plugin marketplace add ririnto/agent-browser-plugin
claude plugin install agent-browser-plugin@agent-browser-plugin
```

### Codex

```sh
codex plugin marketplace add ririnto/agent-browser-plugin
codex plugin add agent-browser-plugin@agent-browser-plugin
```

If you already use the Sinon marketplace in either client, install `agent-browser-plugin@sinon`.

### Cursor

In **Customize**, choose **From GitHub Repository**, enter `https://github.com/ririnto/agent-browser-plugin`, and install **Agent Browser MCP**.
Start a new Agent conversation after installation.
