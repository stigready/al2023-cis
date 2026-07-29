# Changelog

Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.2.3-private-review] - 2026-07-29

### Added
- Initial StigForge export of matrix role `al2023_cis`.
- OpenSCAP verify evidence bundles per profile under `compliance/releases/`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.97%** (floor 90.0%) · gate **PASS** · evidence `20260729T082601Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **97.01%** (floor 90.0%) · gate **PASS** · evidence `20260729T082819Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30435216810
- Factory commit: `e8e323a3af3258bee63ebc1a873ba26c0cc12049`

## [0.2.1-private-review] - 2026-07-28

### Changed
- Galaxy-style layout: Ansible role at repository root; evidence under `compliance/`.
- Private review tag `v0.2.1-private-review` (supersedes nested `roles/<role>/` export).

## [0.2.0-private-review] - 2026-07-26

### Added
- First private StigForge export to `stigready/*` (factory review; nested role path).
