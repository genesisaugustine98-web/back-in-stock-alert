# Start here — back-in-stock-alert

1. Run `agent-pickup --brief`.
2. Read `STATUS.md` for current state and the next safe action.
3. Read the entry points below before editing.
4. If memory and code disagree, verify in the tree and fix `STATUS.md`.

## What this is

Shopify app (Node/React template) for back-in-stock alerts. Uses the Shopify CLI and App Bridge/Polaris.

## Entry points

- `web/` — app server and frontend
- `shopify.app.toml` — app configuration
- `package.json` — Shopify CLI scripts

## Verify / run

```bash
npm install
npm run build
```

## Source of truth

`docs/agent/STATUS.md` is the only current-state document. Verify it against the tree.

Keep this file short. It is a router, not a transcript.
