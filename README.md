# DAO-Originations

Governance and treasury data for every DAO tracked by the platform. One folder
per DAO — separate from NFT-Collections so a community can adopt DAO tracking,
NFT tracking, or both. Fed by the same `platform-crons` engine.

## DAOs
- `aDAO/`      — Alliance DAO. Reference tenant.
- `Lion-DAO/`  — (placeholder)

## Per-DAO layout
- `treasury/`   — token holdings, total value
- `positions/`  — TLA LP positions + other DeFi positions
- `governance/` — proposals, votes, participation
- cron outputs added as the DAO crons land.

Adding a DAO = add a folder with this layout. Nothing else restructures.
