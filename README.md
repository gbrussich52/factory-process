# factory-process

Team operating loop for Grok Bot: spec first, goldens, cheap drafts, no FYI ping.

## Surfaces

- **Cursor IDE (this folder):** install as a local Agent Plugin at `~/.cursor/plugins/local/factory-process`.
- **Grok Bot:** does **not** load `~/.cursor/plugins/local`. Grok Bot runs the same two skills as user skills after they are saved in the Grok Bot skill library.
- **Marketplace:** submitted 2026-09-16 via `cursor.com/marketplace/publish` (Thanks for applying). Awaiting Cursor review. Not cursor.directory.

## Skills

- `factory-process` — start any feature, product, or team task on Grok Bot
- `board-handoff` — route work between Grok Bots

Source of truth for skill bodies: `/workspace/grokbot-process-spec.md` on the Grok Bot computer (Architect owns the spec).

## Not included

No MCP, hooks, rules, agents, or secrets. Not a money SKU. Does not wrap legalaimcp, last30days, or Neuron.
