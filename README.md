# Lens plugins

The Lens skill and MCP server for AI coding agents. [Lens](https://lens.whitehyun.com) is a macOS HTTP(S) debugging proxy; this plugin lets an agent read the traffic it captures and, when you allow it, change Lens's rules.

## Before you install

1. Install Lens in `/Applications`.
2. In Lens › Settings › MCP, turn on **Allow AI clients to read captured traffic**. Turn on **Control** too if the agent should change rules.

## Claude Code

```
/plugin marketplace add WhiteHyun/lens-plugins
/plugin install lens@lens
```

## Codex

```
codex plugin marketplace add WhiteHyun/lens-plugins
```

Then install **Lens** from the Plugins directory.

If you already added Lens with `claude mcp add` or `codex mcp add`, the plugin's server runs the same command, so you can keep either.

## Updating

This repository follows Lens releases. The skill here is the one bundled in that Lens version.
