# Changelog

All notable changes to EntropyAudit are documented in this file.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Rule wording is being reviewed for the next patch.
- A duplicate-seed pattern for generator wrappers is being sketched.

## [1.0.0] - 2026-05-19

### Added

- Stable rule set EA001-EA006, each with a written exploitability rationale.
- Exit codes: 0 clean, 1 findings, 2 usage error.

## [0.7.0] - 2025-04-08

### Added

- Reused nonce and IV constant detection (EA005).
- Fixed-salt detection for password hashing (EA006).

## [0.6.0] - 2024-03-12

### Added

- Weak hash detection for password handling, md5 and sha1 (EA004).
- Sample pair: `samples/vulnerable_auth.py` and `samples/clean_auth.py`.

## [0.5.0] - 2023-02-14

### Added

- Time-seeded generator detection (EA003).
- Markdown report output.

## [0.4.0] - 2022-01-25

### Added

- `random` versus `secrets` misuse detection (EA002).
- Context tracking for imported aliases.

## [0.3.0] - 2020-12-01

### Added

- Predictable seed detection (EA001) with a per-line rationale.
- Machine-readable JSON findings.

## [0.2.0] - 2019-10-15

### Added

- AST-based file walker with directory recursion.
- First six-rule scaffold and the initial test suite.

## [0.1.0] - 2018-07-03

### Added

- First public release: single-file randomness scan.
