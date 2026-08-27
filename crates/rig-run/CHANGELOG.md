# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.43.0](https://github.com/0xPlaygrounds/rig/compare/rig-run-v0.42.0...rig-run-v0.43.0) - 2026-08-27

### Added

- [**breaking**] finish the data layer — blessed ModelTurn conversion, counter/newtype ids, owned dispatch, serde across the protocol surface ([#2419](https://github.com/0xPlaygrounds/rig/pull/2419)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2419
- [**breaking**] event-sourced hook state — RunEntry log on AgentRun replaces the durable Scratchpad snapshot ([#2408](https://github.com/0xPlaygrounds/rig/pull/2408)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2408
- [**breaking**] transport middleware + run lifecycle hooks (on_run_start/on_run_settled, durable Scratchpad) ([#2407](https://github.com/0xPlaygrounds/rig/pull/2407)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2407
- [**breaking**] lower ModelHandle and the erased tool set into rig-core; pure rig_run::prepare_request ([#2405](https://github.com/0xPlaygrounds/rig/pull/2405)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2405
- [**breaking**] rig-run — extract the sans-IO run protocol out of rig-agent (RunSpec, TurnTools, transcript validator, counter RunId) ([#2403](https://github.com/0xPlaygrounds/rig/pull/2403)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2403

### Other

- idiomatic Rust sweep across the workspace ([#2409](https://github.com/0xPlaygrounds/rig/pull/2409)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #2409

### Contributors

* [gold-silver-copper](https://github.com/gold-silver-copper)
