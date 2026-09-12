# Changelog

Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.3.0] - 2026-09-12

### Changed
- StigForge export refresh for `al2023_cis` at `0.3.0`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.97%** (floor 90.0%) · gate **PASS** · evidence `20260912T135819Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **97.01%** (floor 90.0%) · gate **PASS** · evidence `20260912T140019Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/34693316989
- Factory commit: `562a1f7c1a8e19235ee26e972174d1be6c88998c`

## [0.2.4] - 2026-07-30

### Changed
- StigForge export refresh for `al2023_cis` at `0.2.4`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.97%** (floor 90.0%) · gate **PASS** · evidence `20260729T223619Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **97.01%** (floor 90.0%) · gate **PASS** · evidence `20260729T223847Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30496236357
- Factory commit: `7f7cafc85a392bf2a7eb04f1b979185dbcdf5530`

## [0.2.4-private-review] - 2026-07-29

### Changed
- StigForge export refresh for `al2023_cis` at `0.2.4-private-review`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.97%** (floor 90.0%) · gate **PASS** · evidence `20260729T100447Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **97.01%** (floor 90.0%) · gate **PASS** · evidence `20260729T100653Z`
  - Remaining counted failures: `file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30440754045
- Factory commit: `c481b47d629f5bc2357a86a933aa6f94f5245fce`

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
