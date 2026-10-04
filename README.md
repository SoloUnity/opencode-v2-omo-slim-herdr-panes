# opencode-v2-omo-slim-herdr-panes

Shows OpenCode V2 child sessions in Herdr panes.

Requires Node.js 22+, Herdr, and the local shared OpenCode service.
Clone into `~/.config/opencode/plugins/opencode-v2-omo-slim-herdr-panes`.
Add to `~/.config/opencode/cli.json`:

```json
{
  "plugins": ["./plugins/opencode-v2-omo-slim-herdr-panes"]
}
```

Run the full OpenCode terminal inside Herdr. The plugin opens Mini panes for
child sessions and closes them when work ends. Remote and standalone servers are unsupported.

Tests: `npm test`.
