# Edvantage fork

This is Edvantage's fork of [scaccogatto/okf-skills](https://github.com/scaccogatto/okf-skills)
by Marco Boffo (MIT). The original `LICENSE` and `NOTICE` apply unchanged; the vendored OKF
specification is (c) Google LLC under Apache 2.0.

## Install from this fork

```text
/plugin marketplace add Edvantage26/okf-skills
/plugin install okf@edvantage-okf
```

## Remotes

- `origin`: this fork. All Edvantage changes land here.
- `upstream`: the original, fetch only. Bring changes in with `git fetch upstream` and a merge or
  cherry-pick, reviewed like any other change.

## Fork changes

Keep this list current so a merge from upstream knows what to preserve.

| Date | Change | Files |
|---|---|---|
| 2026-10-30 | Marketplace renamed to `edvantage-okf`, owner Edvantage (plugin author unchanged) | `.claude-plugin/marketplace.json` |
| 2026-10-30 | This file | `FORK.md` |
