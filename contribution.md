# Contributing to the Living Guidelines and Standards for Evidence Synthesis in Environmental Management

Thanks for your interest in improving these guidelines. This repository hosts a **living** version of the guidance so that corrections, clarifications, new examples, and updates can be proposed transparently and credited to contributors.

## What counts as a contribution?

Contributions can be small or large. Examples include:

- Fixing typos, broken links, formatting issues
- Clarifying wording, adding examples, improving structure
- Updating references or adding missing citations/DOIs
- Proposing new sections (with rationale and supporting sources)
- Translating or improving language accessibility
- Adding templates, checklists, figures, or worked examples
- Reporting problems (issues), suggesting improvements, or asking questions that lead to changes

If you are unsure, open an issue — we’ll help route it.

## How to contribute (quick start)

### Option A: Suggest changes (no GitHub workflow experience needed)
1. Go to the relevant page/file.
2. Click **“Open an issue”** (or “New issue”).
3. Describe:
   - What should change
   - Why (and include sources/links if relevant)
   - Where in the text the change should occur (section / heading / file)

### Option B: Propose an edit via Pull Request (PR)
1. **Fork** the repository (top-right “Fork” button).
2. Create a new branch (e.g., `fix-typos-section-8` or `update-meta-regression-text`).
3. Make your edits.
4. Open a **Pull Request** to the main repo with a short description of the change.

If you want to contribute but aren’t comfortable with Git, you can also email a suggested patch to the maintainers (see “Contact”), and we can open a PR on your behalf while preserving your authorship/credit.

## Credit and recognition

We want contributions to be citable, transparent, and fairly credited.

### GitHub credit
- All merged PRs preserve contributor identity through GitHub history.
- We encourage contributors to ensure their Git commits are associated with their GitHub account.

### Authorship in releases
- Periodically, we create a dated **release** of the guidelines (e.g., `v2026.01`).
- Each release includes an automatically generated **Contributors** list and summary of changes.
- Contributors to that release will be acknowledged in release notes.

### Citation and acknowledgement
- This repository includes a `CITATION.cff` file so that releases can be cited.
- If you make a substantial contribution (e.g., new section, major revision, new tool/template), we will:
  - acknowledge you prominently in the release notes, and
  - (where appropriate) invite you to co-author any formal editorial describing the living guideline model or major guideline updates.

## What makes a PR easy to merge?

A good PR is:
- **Focused**: one topic or fix per PR where possible
- **Traceable**: includes justification and references where needed
- **Readable**: edits are clear and consistent with the existing style
- **Tested**: you ran Quarto render locally if you changed structure, references, or citations

### If your change affects meaning
Please include:
- a brief rationale (“why this change improves the guideline”)
- the evidence/source supporting it (paper, report, dataset, policy document)

## Editorial and governance principles

These guidelines aim to be:
- **Transparent**: changes are tracked via issues/PRs and versioned releases
- **Evidence-informed**: substantive changes should be justified with sources
- **Practical**: clarity and usability matter
- **Inclusive**: respectful tone; contributors from different disciplines and regions welcome

### Decision-making
- Maintainers review PRs and may request revisions.
- When there is disagreement, we prefer:
  1) documenting uncertainty and alternatives, or
  2) writing conditional guidance (“in X context, do Y; otherwise, do Z”),
  rather than forcing consensus prematurely.

### Conflicts of interest
If your proposed change relates to your own work, tools, or commercial products, please disclose that in the PR description or issue. This does not disqualify a contribution — it helps us keep the process transparent.

## Style guide (brief)

- Use clear headings and short paragraphs.
- Prefer active voice and concrete guidance.
- Avoid unexplained acronyms (define once).
- When adding citations, include DOI where possible.
- Keep examples minimal but realistic.
- For tables, prefer Markdown tables or Quarto-friendly formats.

## Local build (optional but recommended)

If you can, please check that the site builds locally:

```bash
quarto render
