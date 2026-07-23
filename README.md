# Repository Architecture for Agentic Systems (RAAS)

RAAS is an architectural pattern that treats a software repository itself as an active participant in agent onboarding and execution, rather than a passive collection of source code and documentation. Instead of relying on increasingly capable models to infer repository structure, RAAS organizes deterministic knowledge — command metadata, workflow contracts, semantic indexes, structured documentation — into progressively discoverable artifacts, so that reasoning is reserved for the problems that genuinely require it.

This repository holds the proposal for that pattern.

## Contents

| Path | What it is |
|---|---|
| [`PROPOSAL.md`](./PROPOSAL.md) | The proposal itself, in Markdown. This is the working source of truth. |
| [`paper/raas.pdf`](./paper/raas.pdf) | A rendered PDF of `PROPOSAL.md`, for reading or sharing outside of git. |
| [`TODO.md`](./TODO.md) | What's outlined but not yet written — missing chapters, open structural questions, loose ends. |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | How to propose changes. |
| [`LICENSE`](./LICENSE) | CC BY 4.0. |

## Status

This is a proposal in progress, not a finished paper. `PROPOSAL.md` currently covers the Abstract, Introduction, Historical Foundations, Terminology, the core Repository Architecture concepts (Context, Intent, Deterministic Knowledge, Workflow Knowledge, Reasoning, Progressive Discovery), the Repository Components chapter, the seven Architectural Principles, a comparison against existing approaches (Retrieval-Augmented Generation, Knowledge Graphs, the Model Context Protocol), a Case Study of a real reference implementation ([reserve](https://github.com/derickschaefer/reserve), an unofficial FRED CLI), and a Discussion (Benefits, Tradeoffs, Limitations, Future Research). Both chapters the Abstract promises — the comparison and the reference implementation — are now written.

What remains is a Conclusion, not yet assembled from the loose fragments described in `TODO.md`, plus a handful of smaller loose ends (an open question about whether "The Determinism Continuum" needs its own chapter, and some pattern-vocabulary terms named in an early outline but not all formally defined). See `TODO.md` for the full backlog.

## License

This work is licensed under [CC BY 4.0](./LICENSE) — you can share and adapt it with attribution.
