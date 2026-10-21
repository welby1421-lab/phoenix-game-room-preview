# ARCHITECTURE.md — phoenix-game-room-preview

## What this is
Placeholder repo: a README only ("Phoenix Game Room Front Desk preview (Render-ready)").
There is no application code here, nothing deploys from this repo, and no Render
service is attached to it.

## Do not break
- **Do not build here.** This is a placeholder; building app code in it creates a
  divergent fork that will confuse every bot that touches it.
- The live Phoenix Game Room / Gameroom360 code lives in the **altiras360** GitHub
  org, primarily `altiras360/phoenix-gameroom-app` (main Next.js app). Live VPS
  mirrors exist as `altiras360/phoenix-player-portal`, `phoenix-agent-desk`, and
  `phoenix-gameroom-ledger`; `altiras360/phoenix-gameroom-vps-clone` is a snapshot
  copy of the live VPS code, and `altiras360/transaction-ticker` is the hourly
  read-only analytics ticker.
- `welby1421-lab` also holds many other `phoenix-*` placeholder/probe repos —
  none of them are the live code either.

## Related and look-alike repos
- `altiras360/phoenix-gameroom-app` — the live app; build here.
- `welby1421-lab/phoenix-*` — placeholders/probes like this one; do not build.
- `Raccoon-Pay/RaccoonPay` — design-only placeholder for a different brand
  (listed so nobody confuses the placeholder pattern across brands).

## Deploy / data / integrations
None. No stack, database, migrations, or external services in this repo.

## Keep this file current
If this repo ever gains real code, update ARCHITECTURE.md in the same PR that adds it.
