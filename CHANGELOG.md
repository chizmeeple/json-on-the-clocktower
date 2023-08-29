# json-on-the-clocktower

## 0.0.22

### Patch Changes

- feat: add remote_image to roles ([#72](https://github.com/chizmw/json-on-the-clocktower/pull/72))

## 0.0.21

### Patch Changes

- chore: add new-character script helper ([#66](https://github.com/chizmw/json-on-the-clocktower/pull/66))

- chore: update sanity test to include extra-characters/ automatically ([#66](https://github.com/chizmw/json-on-the-clocktower/pull/66))

- chore: add vscode extension recommendations ([#69](https://github.com/chizmw/json-on-the-clocktower/pull/69))

- feat: add plaguedoctor character ([#68](https://github.com/chizmw/json-on-the-clocktower/pull/68))

- chore: ignore test results in git ([#68](https://github.com/chizmw/json-on-the-clocktower/pull/68))

- chore(deps-dev): ensure we have our key python dev deps ([#69](https://github.com/chizmw/json-on-the-clocktower/pull/69))

- feat: add bootlegger character ([#66](https://github.com/chizmw/json-on-the-clocktower/pull/66))

## 0.0.20

### Patch Changes

- chore(deps): certifi (2023.5.7 -> 2023.7.22) ([#58](https://github.com/chizmw/json-on-the-clocktower/pull/58))

- chore: :label: add labeler support for 'deps-dev' tag ([#56](https://github.com/chizmw/json-on-the-clocktower/pull/56))

## 0.0.19

### Patch Changes

- chore(deps-dev): bump black from 23.3.0 to 23.7.0 ([#49](https://github.com/chizmw/json-on-the-clocktower/pull/49))

- docs(changeset): bump mypy from 1.3.0 to 1.4.1 ([#44](https://github.com/chizmw/json-on-the-clocktower/pull/44))

- docs(changeset): bump pylint from 2.17.4 to 2.17.5 ([#45](https://github.com/chizmw/json-on-the-clocktower/pull/45))

- docs(changeset): bump types-requests from 2.31.0.0 to 2.31.0.2 ([#46](https://github.com/chizmw/json-on-the-clocktower/pull/46))

- docs(changeset): bump actions/setup-python from 2 to 4 ([#54](https://github.com/chizmw/json-on-the-clocktower/pull/54))

- docs(changeset): bump chizmw/changesets-changelog-info from 0.0.15 to 0.1.1 ([#43](https://github.com/chizmw/json-on-the-clocktower/pull/43))

- docs(changeset): bump click from 8.1.4 to 8.1.6 ([#48](https://github.com/chizmw/json-on-the-clocktower/pull/48))

## 0.0.18

### Patch Changes

- feat: :label: add workflow and config for [multi-labeler](https://github.com/marketplace/actions/multi-labeler) ([#50](https://github.com/chizmw/json-on-the-clocktower/pull/50))

- fix: trailing whitespace and missing '---' in dependabot config ([#50](https://github.com/chizmw/json-on-the-clocktower/pull/50))

- fix: 'vv' mistake in version replacement ([#50](https://github.com/chizmw/json-on-the-clocktower/pull/50))

## 0.0.17

### Patch Changes

- add "how to get specific version" to README ([#39](https://github.com/chizmw/json-on-the-clocktower/pull/39))

- Create dependabot.yml ([#41](https://github.com/chizmw/json-on-the-clocktower/pull/41))

## 0.0.16

### Patch Changes

- fix: use fetch-depth=0 so we get all the tags in Changeset Release ([#36](https://github.com/chizmw/json-on-the-clocktower/pull/36))

## 0.0.15

### Patch Changes

- add version status badge to readme ([#33](https://github.com/chizmw/json-on-the-clocktower/pull/33))

## 0.0.14

### Patch Changes

- fix: don't try to create tags that already exist ([#30](https://github.com/chizmw/json-on-the-clocktower/pull/30))

## 0.0.13

### Patch Changes

- fix changeset-release Push Tags step ([#27](https://github.com/chizmw/json-on-the-clocktower/pull/27))

## 0.0.12

### Patch Changes

- fix: quote python version value in version-updater workflow ([#24](https://github.com/chizmw/json-on-the-clocktower/pull/24))

## 0.0.11

### Patch Changes

- fix workflows/update-doc-version.yml ([#22](https://github.com/chizmw/json-on-the-clocktower/pull/22))

## 0.0.10

### Patch Changes

- fix repo check in workflow ([#19](https://github.com/chizmw/json-on-the-clocktower/pull/19))

- fix yarn package version ([#21](https://github.com/chizmw/json-on-the-clocktower/pull/21))

- add missing pytest dependency ([#14](https://github.com/chizmw/json-on-the-clocktower/pull/14))

- add workflow to update version refs in docs ([#21](https://github.com/chizmw/json-on-the-clocktower/pull/21))

- migrate to changesets (from changie) ([#14](https://github.com/chizmw/json-on-the-clocktower/pull/14))

## 0.0.9 - 2023-07-22

## 0.0.8 - 2023-07-21

### Fixed

- actually use harpy data in harpy character file

## 0.0.7 - 2023-07-21

### Added

- add character data for harpy

## 0.0.6 - 2023-07-12

### Changed

- add --force-fetch to morph.cli

## 0.0.5 - 2023-07-11

### Changed

- fix edition metadata; add physicaltoken info

### Fixed

- fix get_edition_for_role() to use "experimental" instead of ""

## 0.0.4 - 2023-06-23

### Added

- use md5 checksums to known when external data has changed

### Fixed

- fix: fetch remote data before loading local files

## 0.0.3 - 2023-06-11

### Added

- add "teams" section to generated JSON

## 0.0.2 - 2023-06-11

### Added

- complete first working version of 'melder'
- add our first ever data/generated/roles-combined.json
- add jinx info to the generated file
- Add content to the README
- replace melder with morph
- add "editions" to morphed json
- add assign pr / project workflows
- add 'release' target rules to Makefile
- poetry add pylint

### Changed

- regenerate with EOF newline
- use meta role names that match nightorder
- run 'make morph' to generate new data
- run: precommit autoupdate
- changes to appease pylint

### Removed

- remove the original implementation (melder)

### Fixed

- ensure generated file has newline at EOF
- fix PYSRC: melder -> morph
- use correct directory in pyling commit hook
