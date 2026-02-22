# Version v0.0.6 Documentation

## Title
Workshop Asset Reorganization into `codex-labs/eli-talk/` and Release Metadata Update

## Quick Diagnostic Read

This version primarily reorganizes workshop asset paths and aligns root documentation to the new layout.

For a fast review, read:

1. `README.md`
2. `CHANGELOG.md`
3. `SECURITY.md`
4. `codex-labs/eli-talk/` (new asset location)

## One-Sentence Objective

Move Eli talk notebooks and dataset into a dedicated subfolder and synchronize release/version documentation so attendees use the correct paths.

## Scope of This Version

The current task context shows a repository-structure change (file relocation) plus documentation updates.
No notebook workflow expansion or dataset schema changes were introduced as part of this release documentation pass.

## What Changed in v0.0.6

### 1) Workshop Asset Relocation to `codex-labs/eli-talk/`

The workshop files were reorganized from `codex-labs/` into a dedicated subfolder:

- `concatenate.ipynb`
- `merge.ipynb`
- `data cleaning.ipynb`
- `df_download.csv`

Why it matters:

- keeps Eli talk materials grouped under a single folder,
- reduces ambiguity if additional workshop tracks/speakers are added later.

### 2) Legacy Top-Level Workshop Paths Removed

The previous copies of the notebooks and dataset under `codex-labs/` were removed from the active layout after relocation.

Why it matters:

- prevents duplicate-path confusion in setup instructions,
- ensures documentation points to one canonical location.

### 3) README Path and Release Pointer Updates

`README.md` was updated to:

- bump the version marker to `v0.0.6`,
- update repository contents to list `codex-labs/eli-talk/*`,
- change the getting-started notebook path from `codex-labs/` to `codex-labs/eli-talk/`,
- refresh release notes references to `docs/version-0.0.6-docs.md`.

Why it matters:

- attendees will open the correct notebooks without path errors,
- release tracking remains synchronized across root docs.

### 4) Changelog Record and Manual Cleanup Marker

`CHANGELOG.md` now contains a `v0.0.6` entry documenting the asset relocation and related documentation updates.

It also flags `codex-labs/eli-talk/.ipynb_checkpoints/` under `### For Deletion` for manual review/removal if those generated artifacts are not intended to be tracked.

Why it matters:

- release history captures the folder migration explicitly,
- generated checkpoint files remain visible for manual cleanup without deleting anything in this task.

### 5) Security Support Matrix Update

`SECURITY.md` supported versions table includes `v0.0.6`.

Why it matters:

- vulnerability reporting guidance now matches the latest documented release version.

### 6) Governance Docs Review Outcome

`CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` were not modified.

Why no change was needed:

- this release changes repository layout and release docs only,
- no contributor process or conduct-policy updates were required.

## File-Level Change Map

- `README.md`
  - version/status updated to `v0.0.6`
  - repository asset paths updated to `codex-labs/eli-talk/`
  - release references updated to `docs/version-0.0.6-docs.md`
- `CHANGELOG.md`
  - added top `v0.0.6` entry documenting relocation + docs updates
  - added manual deletion candidate for `codex-labs/eli-talk/.ipynb_checkpoints/`
- `SECURITY.md`
  - supported versions table includes `v0.0.6`
- `docs/version-0.0.6-docs.md`
  - this detailed release narrative
- `codex-labs/eli-talk/`
  - new canonical directory for the Eli talk notebooks and dataset

## For Deletion Candidate (Not Deleted by Task)

- `codex-labs/eli-talk/.ipynb_checkpoints/`

Reason:

- generated Jupyter checkpoint directory and mirrored CSV/notebook artifacts; typically not needed for published repository source unless intentionally preserved.

## Verification Checklist

- README version marker is `v0.0.6`.
- README repository contents and setup steps reference `codex-labs/eli-talk/`.
- changelog has `v0.0.6` as the top entry and includes a `### For Deletion` note for the new checkpoint folder.
- security policy lists `v0.0.6` as supported.
- this file exists at `docs/version-0.0.6-docs.md`.

## Recommended Next Actions (24-72 Hours)

1. Decide whether `codex-labs/eli-talk/.ipynb_checkpoints/` should remain tracked and manually remove it if not needed.
2. Consider adding or tightening ignore rules for notebook checkpoint artifacts to avoid repeating manual cleanup.
3. Use one squash-friendly Conventional Commit for the relocation + documentation update set.
