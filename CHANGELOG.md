# Changelog

## 0.1.1 — 2026-10-10

- A signal needs a live page. The operator opens the URL and sets `page` to `live`.
- Scorer refuses parked, dead, unknown, and a URL with no `page`. It still does not fetch the page.

## 0.1.0 — 2026-10-08

- First public MIT release.
- Instrument: a buying signal is a dated, linkable event.
- Banned: no intent score without a URL and a date.
- Scorer `skills/signal-with-a-link/scripts/score.py` (stdlib only): requires `event`, `url`, `date`; refuses firmographic state, stale (>90 days) and future dates, and intent-without-link.
- Kickoff + validate modes in `SKILL.md`.
- Worked examples: good, with-intent, no-url, no-date, intent-only, firmographic.
- Claude Code plugin manifests under `.claude-plugin/`.
