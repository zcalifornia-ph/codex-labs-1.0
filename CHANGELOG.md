# Changelog

Status: workshop repository documentation and notebook assets actively maintained.

## v0.0.6

### Added or Changed
- Reorganized workshop notebooks and dataset into `codex-labs/eli-talk/` (`concatenate.ipynb`, `merge.ipynb`, `data cleaning.ipynb`, and `df_download.csv`) to keep Eli talk materials in a dedicated subfolder.
- Removed the legacy top-level workshop asset copies from `codex-labs/` after relocation to the `eli-talk` subdirectory.
- Moved corresponding Jupyter checkpoint artifacts into `codex-labs/eli-talk/.ipynb_checkpoints/` as part of the same folder restructure.
- Updated `README.md` version marker from `v0.0.5` to `v0.0.6` and refreshed repository-contents, setup, and release-notes paths to use `codex-labs/eli-talk/`.
- Added detailed release documentation: `docs/version-0.0.6-docs.md`.
- Updated `SECURITY.md` supported versions table to include `v0.0.6`.

### For Deletion
- `codex-labs/eli-talk/.ipynb_checkpoints/` (generated notebook checkpoint directory; review and remove manually if not intentionally tracked).

## v0.0.5

### Added or Changed
- Audited root documentation against current repository contents in `docs/`, `learn/`, and root-level markdown files.
- Updated `README.md` version/status and release-notes references to reflect current release tracking.
- Added detailed release documentation: `docs/version-0.0.5-docs.md`.
- Removed references to ignored internal workflow metadata from historical changelog notes.
- Updated `SECURITY.md` supported versions table to include `v0.0.5`.

### For Deletion
- `codex-labs/.ipynb_checkpoints/` (generated notebook checkpoint directory; review and remove manually if not intentionally tracked).

## v0.0.4

### Added or Changed
- Reframed `README.md` as an attendee repository output for CODEX LABS 1.0 and updated project-intro wording to match workshop participation context.
- Added `README.md` workshop context details: workshop title, schedule, venue, speaker lineup (Eli Lamzon and Meelo Piezas), and highlighted tools (`Pandas`, `Matplotlib`, `Seaborn`).
- Updated `README.md` preparation/event wording, including Google Colab as an alternative environment and explicit mention of peer-led guided coding format.
- Updated `README.md` version marker from `v0.0.3` to `v0.0.4` and moved release notes reference to `docs/version-0.0.4-docs.md`.
- Added detailed release documentation: `docs/version-0.0.4-docs.md`.
- Updated `SECURITY.md` supported versions table to include `v0.0.4`.

### For Deletion
- `codex-labs/.ipynb_checkpoints/` (generated notebook checkpoint directory; review and remove manually if not intentionally tracked).

## v0.0.3

### Added or Changed
- Expanded `codex-labs/data cleaning.ipynb` with a full data-cleaning walkthrough, including duplicate detection/removal, missing-value checks, activity label normalization, targeted value correction mapping, date standardization, and IQR-based outlier inspection for `Heart_Rate_BPM`.
- Updated `codex-labs/.ipynb_checkpoints/data cleaning-checkpoint.ipynb` to mirror the notebook execution state for the new cleaning workflow cells.
- Updated `repo/images/project_screen.png` with a refreshed project screenshot.
- Updated `README.md` version marker from `v0.0.2` to `v0.0.3` and pointed release notes to `docs/version-0.0.3-docs.md`.
- Added detailed release documentation: `docs/version-0.0.3-docs.md`.
- Updated `SECURITY.md` supported versions table to include `v0.0.3`.

### For Deletion
- `codex-labs/.ipynb_checkpoints/data cleaning-checkpoint.ipynb` (generated notebook checkpoint artifact; remove before publishing if not intentionally tracked).

## v0.0.2

### Added or Changed
- Updated `README.md` version marker from `v0.0.1` to `v0.0.2`.
- Added `README.md` status/release-notes references and linked current release details.
- Added detailed release documentation: `docs/version-0.0.2-docs.md`.
- Updated `SECURITY.md` supported versions table to include `v0.0.2`.

### For Deletion
- `codex-labs/.ipynb_checkpoints/` (generated notebook checkpoint folder; remove before publishing if not intentionally tracked).

## v0.0.1

### Added or Changed
- Initialized repository metadata and governance docs during repository bootstrap.
- Replaced placeholder `README.md` content with project-specific workshop documentation.
- Added project-specific root policies: `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, and `SECURITY.md`.
- Updated repository ignore rules to exclude internal workflow metadata as required by project policy.
- Kept `LICENSE.txt` on Apache License 2.0 and resolved placeholder identity fields in the appendix example.

### For Deletion
- None from this task context (documentation and policy initialization only).
