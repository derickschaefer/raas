# Contributing

This repository holds a proposal, not shipped software — most of the work at this stage is writing and argument, not code. Contributions of either kind are welcome.

## Before you start

Check [`TODO.md`](./TODO.md) first. It tracks the missing chapters (Relationship to Existing Approaches, Case Study: RESERVE, Discussion, Conclusion), the open structural question about chapter numbering, and a handful of loose ends (duplicate sentences, undefined pattern names). If you want to work on a specific gap, open an issue or claim it there before writing, so two people don't draft the same chapter.

## Proposing changes

- **Small edits** (wording, typos, a clearer sentence) — open a pull request directly against `PROPOSAL.md`.
- **New chapters or substantial additions** — open an issue first describing what you intend to add and how it fits the existing structure. This is a proposal under active development; large additions should be discussed before they're written, so effort isn't wasted on a direction the maintainers don't want.
- **Structural changes** (renumbering chapters, merging sections) — open an issue. The outline vs. current-heading-structure question in `TODO.md` needs to be resolved before large restructuring work happens.

## Terminology consistency

`PROPOSAL.md` defines a fixed vocabulary in its Terminology section (Autonomous Consumer, Repository Architecture, Deterministic Knowledge, Deterministic Artifact, Progressive Discovery, Workflow Contract, Semantic Topic Index, Progressive Understanding). New content should use these terms as defined rather than introducing synonyms. If a new concept genuinely doesn't fit an existing term, propose the new term and its definition explicitly — don't let it drift in silently through a single chapter.

## Style

The paper is written in a formal, academic register: full paragraphs, no marketing language, no unexplained jargon. Each section builds on terms and claims established earlier in the document. When adding a section, look at how neighboring sections are structured (thesis paragraph, elaboration, consequence) and match that shape rather than introducing a new style.

## Building the PDF

`paper/raas.pdf` is rendered from `PROPOSAL.md` via [pandoc](https://pandoc.org/):

```
pandoc PROPOSAL.md -o paper/raas.pdf \
  --pdf-engine=xelatex \
  -V geometry:margin=1in \
  -V mainfont="Georgia" \
  --toc
```

If you change `PROPOSAL.md`, regenerate `paper/raas.pdf` in the same pull request so the two don't drift apart.

## License

By contributing, you agree that your contributions are licensed under the same [CC BY 4.0](./LICENSE) license that covers the rest of this repository.
