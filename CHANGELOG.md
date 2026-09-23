# Changelog

All notable changes to stuxedo.github.io are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v1.0.2

### Fixed
- GitHub Pages was using the legacy branch-deploy build system, which can silently stop auto-deploying with no error recorded anywhere (discovered on SeasonalOverlaysLibrary — its live site served stale content for over an hour with no visible failure). Switched to GitHub Actions-based Pages deployment (`.github/workflows/pages.yml`), making every deploy an ordinary, observable CI run instead.

## v1.0.1

### Fixed
- `README.md` said Stuxedo is "part of the Stux.Group Brand of Companies" directly — the actual chain is Stuxedo → Stux.Cloud → Stux Group Ltd. Corrected to name Stux.Cloud as the direct operator, with Stux Group Ltd's full registration details.

## v1.0.0

### Added
- First version-tracked release of this GitHub Pages redirect repo — `VERSION.md`/`CHANGELOG.md`/`CONTRIBUTING.md`/`commit.sh`+`commit.bat` added, following the standard release-flow convention used across other Stuxedo repos. `README.md`'s header logo already correctly pointed at `https://global.media.stuxedo.com/logo.png` — no content fix needed here, just bringing the repo under version tracking.
