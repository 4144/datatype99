# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]

### Changed

 - Force users to download metalang99 as well, i.e. don't use it as a Git submodule.

### Added

 - Generate `typedef struct <datatype-name> <datatype-name>;` beforehand so `<datatype-name> *` can be used instead of `struct <datatype-name> *` inside variants.

## [0.2.0] - 2020-02-05

### Changed

 - Replace `Epilepsy` with `Metalang99` (more neutral).

## [0.1.0] - 2020-02-04

### Added

 - This excellent project.
