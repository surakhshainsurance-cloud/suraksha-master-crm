# Suraksha Master CRM

Single unified entry point for all Suraksha operations.

## Architecture
- **MP (Multitasker)** — top layer, noise-free output to owner
- **Manager** — security-heavy tasks, spawns workers under it
- **Security** — refinery layer, multiple refineries under it
- **Workers/Bots** — 16 bots, each single-specialist, one job perfect

## Connectors Live
- GitHub: surakhshainsurance-cloud
- Google Drive: surakhshainsurance, manishmodi.1995, gmgopaltraing@gmail.com
- Gmail: connected
- Google Calendar: connected
- Gamma: connected
- Automations: mp-hourly-warehouse-update (every 60 min, Asia/Kolkata)

## Single API Rule
One endpoint. Every connector routes through it. No manual login. No manual copy-paste.

## Dust & Drawdown
- Dust: anything unverified or pending
- Drawdown: anything that can fail or cost tokens

Owner: Manish Modi | Suraksha Talcher