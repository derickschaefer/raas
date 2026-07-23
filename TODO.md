# TODO

`PROPOSAL.md` is essentially done. Three open items remain, all left for manual finishing.

## 1. Conclusion

Not yet written. Four loose paragraphs below read like conclusion material but were never assembled under a heading. The last two overlap — decide whether to keep the echo or cut the duplicate.

> Modern AI architectures increasingly concentrate intelligence before execution. They retrieve more documents, construct larger knowledge graphs, expand context windows, and enrich tool metadata in an effort to reduce uncertainty before a single command is invoked. Progressive Agent Onboarding accepts this trend but asks a different question: rather than making the model progressively smarter about the software, can the software become progressively easier for the model to understand?

> The architectural properties that made command-line systems successful for human operators—small deterministic interfaces, composability, explicit contracts, and progressive composition—also make them exceptionally well suited for autonomous software agents.

> As autonomous agents become first-class participants in software engineering, repository architecture itself becomes part of the execution environment. Software should not merely be executable—it should be progressively understandable.

> Software should not merely be executable—it should be progressively understandable. *(duplicate of the sentence above — cut one)*

## 2. The Determinism Continuum

An early outline had this as a standalone chapter. Its ground is already covered under Repository Architecture (Deterministic Knowledge, Reasoning) — reviewers should decide whether that's sufficient or whether it deserves its own section.

## 3. Unnamed pattern vocabulary

Three ideas are used throughout but never formally named as patterns in writing. Decide whether to name them explicitly or leave them implicit:

- **Progressive Agent Onboarding** — implied throughout, never named as "the pattern."
- **Progressive Retrieval** — never distinguished from Progressive Discovery.
- **Deterministic Composition** — covered by Principle 6, never named.
