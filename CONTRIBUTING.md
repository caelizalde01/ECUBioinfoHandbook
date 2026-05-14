# Contributing

Thank you for your interest in contributing to this project. This repository is intended as a **living document** for the ECU bioinformatics community: a resource that grows, adapts, and improves as methodologies evolve and as new students, researchers, and faculty bring their expertise to it. Contributions of all sizes — from typo fixes to entirely new methodological chapters — are welcomed and encouraged.

This document outlines how to propose changes and what to expect during the review process.

## Philosophy

This project began as a master's thesis and was deliberately released under open licenses (GPL-3.0 for code, CC-BY-SA-4.0 for written content) so that it can continue to serve future cohorts. The original author does not consider this work "finished" — it is a foundation. If a tool becomes obsolete, replace it. If a new method outperforms what's documented here, document it. If a section is unclear, clarify it. The goal is for this resource to remain genuinely useful to the next person who picks it up, whoever and whenever that may be.

## Ways to Contribute

There are many valuable ways to improve this project:

- **Methodological updates** — Replacing deprecated tools, adding new analyses (e.g., single-cell workflows, long-read variants), or refining existing pipeline steps.
- **Code improvements** — Bug fixes, performance optimizations, better error handling, cross-platform compatibility, or refactoring for clarity.
- **Written content** — Correcting errors, improving explanations, expanding sections, adding new chapters, or updating citations and references.
- **Examples and tutorials** — Walkthroughs using new datasets, beginner-friendly explanations of complex steps, or comparative analyses against alternative tools.
- **Documentation** — Improving README clarity, adding installation notes for different systems, or writing troubleshooting guides.
- **Reproducibility** — Pinning dependency versions or environment files (conda, renv).

If you're unsure whether a contribution fits, open an issue first to discuss. There is no contribution too small.

## Getting Started

1. **Fork** this repository to your own GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/caelizalde01/ECUBioinfoHandbook.git
   cd BioinfoHandbook
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b descriptive-branch-name
   ```
   Use a name that briefly describes the change (e.g., `update-deseq2-section`, `fix-hisat2-memory-flag`, `add-salmon-alternative`).
4. Make your changes, commit them with clear messages, and push to your fork.
5. Open a **pull request** against the main repository's `main` branch.

## Submitting Changes

When opening a pull request, please include:

- A clear title describing the change.
- A brief description of **what** changed and **why**.
- For methodological changes, a short justification (e.g., a citation or benchmark showing the new approach is preferable).
- For written content changes, a note if the change is stylistic vs. substantive.

Pull requests will be reviewed in good faith and as time allows. Feedback may be given; don't take it personally — the goal is always to improve the resource, not to gatekeep contributions.

## Code Contribution Guidelines

- **Reproducibility**: If your contribution introduces a new dependency, document it (version-pinned where possible) and update the relevant environment file or installation instructions.
- **Comments**: Code should be readable. Comment non-obvious steps, especially in pipeline scripts where parameter choices matter scientifically.
- **Testing**: If possible, verify your code runs end-to-end on the reference dataset before submitting. Note any datasets or system configurations you tested against in the PR description.

## Written Content Contribution Guidelines

- **Tone and voice**: The intended audience of the guidebook is undergraduate students with a background in biology but not computer science. Refrain from vulgar language, but prioritize comprehension over formality when expanding or revising sections.
- **Citations**: Add proper citations for new methodological claims, tools, or datasets. Follow the existing citation format in the document (APA 7 with numbered superscripts).
- **Structure**: When adding new sections, follow the existing heading hierarchy and document organization. If a major reorganization is warranted, open an issue first or discuss with the current chair of the Department of Biological & Environmental Sciences.

## Attribution and Credit

Because written content is licensed under **CC-BY-SA-4.0**, attribution is both a legal requirement and a feature of the living-document model — it preserves the lineage of who contributed what across generations of revisions.

- All contributors will be acknowledged in the document's contributors list and/or revision history.
- When making substantive revisions (e.g., the addition of a new pipeline), please add yourself to the contributors section at the bottom of this document.
- When building on a specific prior contribution (e.g., expanding a section another contributor wrote), retain the original attribution alongside your own. Do not remove prior contributors.

## Licensing of Contributions

By submitting a pull request, you agree that your contributions will be licensed under the same terms as the rest of the project:

- **Code contributions** are licensed under **GPL-3.0-or-later**.
- **Written content contributions** (prose, documentation, figures) are licensed under **CC-BY-SA-4.0**.

This dual-license structure is what keeps the project open in perpetuity. The ShareAlike clause of CC-BY-SA-4.0 in particular ensures that all future versions of the written content remain freely usable, modifiable, and shareable by anyone who comes after.

If you have questions about licensing compatibility with a contribution you're considering (e.g., incorporating material from another source), please open an issue before submitting.

## Code of Conduct

This project welcomes contributors from all backgrounds and experience levels. Please be respectful, constructive, and patient in all interactions — especially with newcomers to bioinformatics, who are precisely the audience this resource is designed to serve. Disagreements about methodology or approach are welcome and healthy; personal attacks are not.

## Questions

If you're unsure about anything — whether a contribution is appropriate, how to format something, or how to get started — please open an issue. Asking is always preferable to guessing.


# Contributors


 - **Caden Anthony Elizalde (Spring 2026)** - *Created Guidebook, Repository, and RNAseq Differential Expression Pipeline*





---

*This document is itself a living document. If the contribution process can be improved, that improvement is itself a welcome contribution.*
