# Lion-DAO / governance — CURATED (migrated 2026-08-11 from defipatriot/adao_json_storage)

Human-vetted governance corpus: weeks of work validating which proposals,
addresses and messages are trustworthy. This is the class of artifact the
strip PRESERVES — unlike machine-captured series from legacy crons, which are
discarded and re-derived (method-tainted; see SITE-DATA-CONTRACT).

| File | What | Provenance |
|---|---|---|
| `registry.json` | vetted contract address book: per-address `name`/`type`/`validActions` + `lpPools` map. 49 contracts. | hand-curated |
| `proposals.json` | 17 proposals with votes/turnout/quorum/threshold | exported 2026-05-22 — **STALE**, re-derive from chain (queued) |
| `members.csv` | 345 members: address, name, image, staked, VP | snapshot export |

**Known staleness:** `proposals.json` was exported 2026-05-22; proposals since
then are missing. The vetted STRUCTURE is what matters here — the live corpus
should be re-derived from chain into this same shape.
