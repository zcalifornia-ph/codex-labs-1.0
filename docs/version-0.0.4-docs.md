# Version v0.0.4 Documentation

## Title
Attendee Context and Workshop Metadata Alignment for CODEX LABS 1.0

## Quick Diagnostic Read

This version is documentation-focused and records the attendee-facing event context for the workshop repository.

If you need a fast review path, read:

1. `README.md`
2. `CHANGELOG.md`
3. `SECURITY.md`

## One-Sentence Objective

Document this repository as attendee workshop output and align release metadata with the event details announced for February 21, 2026.

## Scope of This Version

This version does not change notebook logic or dataset files.
It updates repository documentation and release-tracking metadata.

## What Changed in v0.0.4

### 1) README Attendee Framing

`README.md` now explicitly positions this repository as attendee work from CODEX LABS 1.0.

Why it matters:

- visitors can quickly understand the repository intent
- context now matches workshop participation rather than generic prep material

### 2) Workshop Context Added

A dedicated `## Workshop Context` section was added to `README.md` with:

- full workshop title
- date and schedule
- venue (`Cultural Center, UP Mindanao`)
- speaker lineup (Eli Lamzon and Meelo Piezas)
- key Python tools (`Pandas`, `Matplotlib`, `Seaborn`)
- format note (guided coding workshop with peer-led mentorship)

Why it matters:

- preserves event context directly in the repository
- improves traceability for attendees and reviewers

### 3) Setup and Event Wording Alignment

`README.md` preparation guidance was adjusted and now includes Google Colab as an alternative environment.
Venue wording in `README.md` was also aligned to event materials.

Why it matters:

- lowers setup friction for users without local IDE readiness
- keeps event metadata consistent throughout the documentation

### 4) Release Metadata Updates

- `README.md` version marker updated from `v0.0.3` to `v0.0.4`
- `README.md` release notes pointer updated to this file
- `CHANGELOG.md` received a top `v0.0.4` entry
- `SECURITY.md` supported versions table now includes `v0.0.4`

Why it matters:

- release traceability is current and consistent across repository docs

## File-Level Change Map

- `README.md`
  - attendee-focused project framing
  - workshop-context section added
  - setup/event wording alignment
  - version bump to `v0.0.4`
  - release-notes reference updated to `docs/version-0.0.4-docs.md`
- `CHANGELOG.md`
  - new top `v0.0.4` section
  - `For Deletion` artifacts note for checkpoint directory
- `SECURITY.md`
  - supported versions table updated with `v0.0.4`
- `docs/version-0.0.4-docs.md`
  - this detailed release narrative

## For Deletion Candidate (Not Deleted by Task)

- `codex-labs/.ipynb_checkpoints/`

Reason:

- generated notebook checkpoint directory; usually excluded from source control unless intentionally retained.

## Verification Checklist

- README version marker is `v0.0.4`.
- README release notes points to `docs/version-0.0.4-docs.md`.
- changelog has `v0.0.4` above `v0.0.3`.
- security policy lists `v0.0.4` as supported.
- this file exists at `docs/version-0.0.4-docs.md`.

## Recommended Next Actions (24-72 Hours)

1. Decide whether to keep or remove `codex-labs/.ipynb_checkpoints/` manually.
2. Review README wording for any additional event details you want publicly visible.
3. Stage all docs changes and apply one Conventional Commit.
