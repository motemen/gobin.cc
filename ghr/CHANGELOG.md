# Changelog

## [v0.10.0](https://github.com/tcnksm/ghr/compare/v0.9.0...v0.10.0) (2018-05-08)

* [incompatible] retrieve owner from origin url first [#87](https://github.com/tcnksm/ghr/pull/87) ([Songmu](https://github.com/Songmu))
* update deps [#88](https://github.com/tcnksm/ghr/pull/88) ([Songmu](https://github.com/Songmu))

## [v0.9.0](https://github.com/tcnksm/ghr/compare/v0.5.4...v0.9.0) (2018-04-07)

* introduce motemen/gobump and adjust releng scripts [#85](https://github.com/tcnksm/ghr/pull/85) ([Songmu](https://github.com/Songmu))
* Retry API Requests up to 3 times on releasing [#84](https://github.com/tcnksm/ghr/pull/84) ([Songmu](https://github.com/Songmu))
* update deps [#83](https://github.com/tcnksm/ghr/pull/83) ([Songmu](https://github.com/Songmu))
* colors on Windows [#72](https://github.com/tcnksm/ghr/pull/72) ([mattn](https://github.com/mattn))
* Fix arguments check [#64](https://github.com/tcnksm/ghr/pull/64) ([kanata2](https://github.com/kanata2))
* follow #68 and #69 [#82](https://github.com/tcnksm/ghr/pull/82) ([Songmu](https://github.com/Songmu))
* Add terminal line-break where it is missing in some CLI error messages [#78](https://github.com/tcnksm/ghr/pull/78) ([aurelienrb](https://github.com/aurelienrb))
* Atomic release (change release strategy to prevent users from seeing empty or halfway release) [#74](https://github.com/tcnksm/ghr/pull/74) ([Songmu](https://github.com/Songmu))
* Update deps [#81](https://github.com/tcnksm/ghr/pull/81) ([Songmu](https://github.com/Songmu))
* Introduce Go1.10 [#80](https://github.com/tcnksm/ghr/pull/80) ([Songmu](https://github.com/Songmu))
* fix CI environment [#79](https://github.com/tcnksm/ghr/pull/79) ([Songmu](https://github.com/Songmu))
* Add pagination to ListAssets call [#61](https://github.com/tcnksm/ghr/pull/61) ([Luzifer](https://github.com/Luzifer))
* Add a slash at the end of endpoint [#59](https://github.com/tcnksm/ghr/pull/59) ([linyows](https://github.com/linyows))
* formatting changes [#62](https://github.com/tcnksm/ghr/pull/62) ([robphoenix](https://github.com/robphoenix))
* Fix typo [#63](https://github.com/tcnksm/ghr/pull/63) ([sanemat](https://github.com/sanemat))
* Fix git config command option in README.md [#58](https://github.com/tcnksm/ghr/pull/58) ([syossan27](https://github.com/syossan27))
* Feature/fix test [#57](https://github.com/tcnksm/ghr/pull/57) ([tcnksm](https://github.com/tcnksm))
* Added Name to solve issue with wrong heading [#56](https://github.com/tcnksm/ghr/pull/56) ([jeppefrandsen](https://github.com/jeppefrandsen))

## 0.5.4 (2017-01-11)

### Added 

- Allow to specify body [#55](https://github.com/tcnksm/ghr/pull/55)

## 0.5.3 (2016-10-31)

### Fixed

- Fix overlapping of DeleteRelease and CreateRelease #52

## 0.5.2 (2016-10-21)

### Fixed

- Output format

## 0.5.1 (2016-10-19)

### Fixed

- Can not use GitHub Enterprise environment #48
- Format verbs shows up on output #50

## 0.5.0 (2016-10)

### Added

- Nothing

### Deprecated

- `-stat` option

### Removed

- Nothing

### Fixed

- Refactoring & Adding a lots of tests

## 0.4.0 (2014-12-17)

### Added

- Support Github Enterprise (supported by [**@zoncoen**](https://github.com/zoncoen))
- Add more tests

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- `--delete` sometimes breaks relase. This is temporary solution.

## 0.3.0 (2014-12-15)

### Added

- [goole/go-github](https://github.com/google/go-github) for GitHub API client
- `--stat` option to show how many tool downloaded
- Color output
- Many refactorings

### Deprecated

- Nothing

### Removed

- Old GitHub API client

### Fixed

- Nothing

## 0.2.0 (2014-12-09)

### Added

- Read `GITHUB_TOKEN` from `gitconfig` file ([**@sona-tar**](https://github.com/sona-tar), [#8](https://github.com/tcnksm/ghr/pull/8))
- When using `--delete` option, delete its git tag
- Support private repository ([**@virifi**](https://github.com/virifi), [#10](https://github.com/tcnksm/ghr/pull/10))
- Many refactoring

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- Nothing

## 0.1.2 (2014-10-09)

### Added

- `--replace` option to replace artifact if it exist
- `--delete` option to delete release in advance if it exist
- [tcnksm/go-gitconfig](https://github.com/tcnksm/go-gitconfig) for extracting git config values

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- Nothing

## 0.1.1 (2014-08-06)

### Added

- Limit amount of parallelism by the number of CPU
- `--username` option to set Github username
- `--token` option to set API token
- `--repository` option to set repository name
- `--draft` option to create unpublished release
- `--prerelease` option to create prelerease

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- Nothing

## 0.1.0 (2014-07-29)

Initial release

### Added

- Add Fundamental features

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- Nothing
