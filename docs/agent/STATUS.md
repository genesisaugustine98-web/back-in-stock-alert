# STATUS — current session handoff

Last updated: 2026-11-14
Commit: 95518a7
Branch: main
Working tree: clean at scaffold time (verify with `git status --short`)
Updated by: opencode — agent memory scaffold bootstrap
Review rule: read this first, then verify it against the tree. Overwrite it before you finish.

## One-line state

The agent memory scaffold was added on top of `95518a7`. No product code
changed in this bootstrap; any claim below is a pointer, not a fresh test result.

## What is true now

- Repository purpose: Shopify app (Node/React template) for back-in-stock alerts. Uses the Shopify CLI and App Bridge/Polaris.
- Entry points: `web/` — app server and frontend; `shopify.app.toml` — app configuration; `package.json` — Shopify CLI scripts.
- Current state authority: this file.

## In-flight work

None. The working tree was clean when the scaffold was committed.

## Verification recorded

- Scaffold is documentation only; no product tests were run during bootstrap.
- `npm install` — not run (install).
- `npm run build` — not run (shopify app build (needs Shopify CLI/auth)).

## Open risks / blockers

- `npm run build`/`dev` require the Shopify CLI and an authenticated app context; they may not run headless in CI.

## Next safe action

1. Run the verify command(s) in `START_HERE.md` and confirm they pass on this commit.
2. Then make the scoped change and record the real result here.
