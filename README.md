# RhythmAI Release Metadata

`releases.json` is the machine-readable release history for
[RhythmAI](https://hub.docker.com/r/rhythmai/rhythmai): version, date,
customer-facing release notes (`summary` + `highlights`), whether a release
is app-image-only (`appOnly`), and which deployment services it changed
(`servicesChanged`).

RhythmAI deployments read this file to power the in-app update check
(Settings > About), one-click upgrade eligibility, and the span-aware
update scripts. It is updated as part of every release cut.

This repository contains no source code.
