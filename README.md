# Smart Service Planner

**Your day, thoughtfully laid out.**

An offline first day planner for people whose work happens at addresses such as mobile service workers. Android app plus a
Windows companion. I made this app for my wife and I to improve our quality of work
life. I hope it improves yours too.

## Features

- Flexible appointment windows (30 minutes to 4 hours) that can overlap — real field
  schedules aren't tidy hour blocks.
- One-tap visit outcomes — Made, Missed, Declined — and linked rescheduling that keeps
  history instead of rewriting it.
- Remembered names and addresses with per-person Access Notes (gate codes, "call first
  to put away dogs").
- Printable day, week, and month schedules. Paper still works.
- Monthly calendar with workload bars and outcome markers.
- Fully offline: every change saves immediately to a local SQLite database.
- Optional, always off by default: encrypted backups, device-to-PC transfer over your
  own Wi-Fi, cloud backup to your own account, and small-team visit sharing. No
  feature ever requires an account.

## Privacy

Your data stays on your devices. No developer server, no account, no telemetry, no
data collection — nothing to opt out of. Optional cloud backup talks directly to your
own storage account. The schedule database stores no medical information.

## Codebase

Rust + Tauri v2, SQLite (rusqlite), hand-written HTML/CSS/JS interface. One codebase
for Android and Windows.

## Status

In active development — no installable release yet. The interface and data model are
complete as a verified browser prototype; native packaging is in progress. Watch
Releases for the first test APK.

## License

[AGPL-3.0](LICENSE) — free to use, inspect, and improve.
