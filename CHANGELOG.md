# Changelog

All notable changes to this repository are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
This project is pre-1.0 and research-grade — expect breaking changes.

## [Unreleased]
### Added
- Community-health files: LICENSE (MIT), CONTRIBUTING, CODE_OF_CONDUCT, SECURITY,
  issue/PR templates, CHANGELOG, and `.gitattributes` (LF enforcement for PBIP text).
- README overhaul for community & discoverability, plus a "Getting Started" that documents the
  required PBIR preview feature.
- Star-schema diagram (`docs/assets/star-schema.svg`) embedded in the README.
- GitHub Pages site (served from `docs/`) publishing the build recap, with a `docs/index.html` landing redirect.

### Changed
- Rebranded `docs/session-recap.html` to the Datapot Design System (Microsoft Fluent–inspired light
  theme; Plus Jakarta Sans / Public Sans / JetBrains Mono; brand gradient; sentence case, no emoji),
  added links back to the repository, and expanded the context for readers arriving from the web.
- Genericized the `DataFolder` parameter and de-personalized the non-ASCII path notes.
- Report now opens on the **Overview** page by default.
- Normalized all TMDL files to LF (they had been re-saved as CRLF by Power BI Desktop).

## [0.1.0] - 2026-06-16
### Added
- Initial public release: multi-report PBIP monorepo scaffold.
- Report 01 — Branch & Channel Performance (banking, BankDIAD dummy data): TMDL semantic model
  (3 facts, 6 dimensions, 22 measures, 11 relationships) + PBIR report with 3 pages
  (Overview, Channel Performance, Branch Scorecard).
- Repo-wide docs, conventions, shared Datapot theme and templates, and a session recap.
