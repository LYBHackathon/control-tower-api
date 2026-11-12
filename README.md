# control-tower-api

Backend for the Order-to-Delivery Control Tower, Problem Statement 3 of the LYB Mumbai Hackathon 2026 (Round 2).

All data in this project is fictional. "Plant X" is the fictional company from the hackathon brief.

## Status

Design and planning only. No application code has been written yet.

## Documents

| Document | Purpose |
|---|---|
| [DESIGN.md](DESIGN.md) | Engineering design: requirements mapping, architecture, domain model, API and event contracts, ETA and risk calculation, security, verification and demo script |
| [PHASES.md](PHASES.md) | Execution plan for three owners: phases, exit criteria, critical path and cut list |
| [AI_USAGE.md](AI_USAGE.md) | Declaration of generative AI use, required by the hackathon rules |

These are the canonical copies. The web repository, [control-tower-web](https://github.com/LYBHackathon/control-tower-web), links here.

## What this repository will contain

The API, the ETA and risk engine, the replay simulator, fixtures, migrations and tests. See DESIGN.md section 4.6.

## Branching

`main` always runs. Work happens on `feat/<area>-<short-name>` branches and merges by pull request with one review.
