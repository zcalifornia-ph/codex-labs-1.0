# Version v0.0.3 Documentation

## Title
Data-Cleaning Workflow Expansion for CODEX LABS 1.0

## Quick Diagnostic Read

This version extends the workshop’s notebook content with hands-on cleaning steps and updates release metadata accordingly.

If you are reviewing this release quickly, read:

1. `codex-labs/data cleaning.ipynb`
2. `README.md`
3. `CHANGELOG.md`

## One-Sentence Objective

Capture and document the newly added practical data-cleaning notebook sequence so workshop participants can follow a complete cleaning pipeline in one place.

## Scope of This Version

This version primarily updates workshop learning artifacts:

- notebook workflow depth (`data cleaning.ipynb`)
- screenshot asset refresh (`repo/images/project_screen.png`)
- release metadata synchronization (`README.md`, `CHANGELOG.md`, `SECURITY.md`)

## What Changed in v0.0.3

### 1) Data-Cleaning Notebook Expansion

`codex-labs/data cleaning.ipynb` was extended with additional executed cells that now walk through:

- unique-value inspection for activity normalization
- duplicate counting and duplicate-row inspection
- missing-value checks and missing-value counts
- duplicate removal and post-cleanup validation
- activity string cleanup using `strip()` + `title()`
- correction mapping for known category typos (`Ggym` -> `Gym`, `Cykle` -> `Cycle`)
- date parsing/standardization via `pd.to_datetime(..., format='mixed')`
- IQR-based outlier detection on `Heart_Rate_BPM`

Why it matters:

- participants can see a realistic end-to-end cleaning flow instead of isolated transformations
- the notebook now includes concrete checks before and after each cleaning step

### 2) Notebook Checkpoint Mirror

`codex-labs/.ipynb_checkpoints/data cleaning-checkpoint.ipynb` changed in lockstep with the notebook updates.

Why it matters:

- this reflects notebook execution state, but checkpoint files are usually generated artifacts rather than source-of-truth content

### 3) Visual Asset Refresh

`repo/images/project_screen.png` was updated.

Why it matters:

- the README project preview now reflects the latest workshop state

### 4) Release Metadata and Documentation Alignment

- `README.md` version updated to `v0.0.3`
- `README.md` repository contents updated to explicitly list `codex-labs/data cleaning.ipynb`
- `README.md` release notes pointer updated to this file
- `CHANGELOG.md` received a top `v0.0.3` entry
- `SECURITY.md` supported versions table now includes `v0.0.3`

Why it matters:

- readers can quickly identify the latest version and find detailed release context
- governance metadata remains consistent with the newest release

## File-Level Change Map

- `codex-labs/data cleaning.ipynb`
  - added major cleaning walkthrough cells and outputs
- `codex-labs/.ipynb_checkpoints/data cleaning-checkpoint.ipynb`
  - updated generated checkpoint state
- `repo/images/project_screen.png`
  - refreshed project screenshot
- `README.md`
  - version bump to `v0.0.3`
  - status line update
  - repository contents update
  - release-notes pointer update
- `CHANGELOG.md`
  - new `v0.0.3` section
  - deletion candidate documented
- `SECURITY.md`
  - supported versions table update
- `docs/version-0.0.3-docs.md`
  - this detailed release narrative

## For Deletion Candidate (Not Deleted by Task)

- `codex-labs/.ipynb_checkpoints/data cleaning-checkpoint.ipynb`

Reason:

- generated notebook checkpoint artifact; typically excluded from source control unless intentionally retained.

## Verification Checklist

- README version marker is `v0.0.3`.
- README points release notes to `docs/version-0.0.3-docs.md`.
- changelog has `v0.0.3` above `v0.0.2`.
- security policy lists `v0.0.3` as supported.
- this file exists at `docs/version-0.0.3-docs.md`.

## Recommended Next Actions (24-72 Hours)

1. Decide whether `codex-labs/.ipynb_checkpoints/` should remain tracked or be removed manually.
2. Run through the new `data cleaning.ipynb` cells once end-to-end to verify workshop flow clarity.
3. Stage all changed files and apply a single Conventional Commit for this release update.
