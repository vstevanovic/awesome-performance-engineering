# Changelog

Notable changes to this list are documented in this file, grouped by date — the list is continuously curated rather than versioned. Format inspired by [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## 2026-07-15

### Changed

- Replaced Grafana Beyla with OpenTelemetry eBPF Instrumentation (OBI) — Grafana Labs donated Beyla to OpenTelemetry in May 2025; `grafana/beyla` is now a downstream distribution of the upstream project.
- Moved Redash from Legacy & Historical back to Visualization & Dashboards — the project was revived as a community-maintained effort with regular releases (v26.3.0, March 2026).
- Dropped the active (🟢) indicator from Chaos Monkey — no commits since October 2024.
- Fixed NeoLoad capitalization.

### Removed

- Dredd — repository archived by its owner in November 2024; last release dates from 2021.
- Grafana OnCall — OSS project entered maintenance mode in March 2025 and was archived on 2026-03-24; superseded by the commercial Grafana Cloud IRM.
- Yellowlab Tools — no maintainer activity since November 2023.
- Moogsoft — absorbed into Dell AIOps following the 2023 acquisition; no longer a standalone product.
