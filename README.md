# cricket-live

Live cricket scores, IPL tracking, and match alerts for OpenClaw.

An [OpenClaw](https://openclaw.ai) skill for real-time cricket scores, match details, upcoming fixtures, and automated alerts. Pure bash — no Python, no Node, just `curl` and `jq`.

## Features

- 🏏 **Live scores** — ball-by-ball updates for ongoing matches
- 📊 **Match details** — scorecards, partnerships, bowling figures
- 📅 **Upcoming matches** — fixtures with dates and venues
- 🏆 **IPL tracking** — standings, schedules, team stats
- 🔔 **Match alerts** — automated notifications via cron
- 🔍 **Search** — find any match by team or tournament

## Requirements

- `curl` and `jq`
- `CRICKET_API_KEY` environment variable

## Install

```bash
clawhub install cricket-live
```

## Usage

Ask your AI agent:

> "What's the score of the India match?"
> "Show me upcoming IPL fixtures"
> "Set up alerts for India vs Australia"
> "Show recent cricket results"

## Scripts

| Script | Description |
|--------|-------------|
| `live-scores.sh` | Current match scores |
| `match-details.sh` | Detailed scorecard |
| `upcoming-matches.sh` | Future fixtures |
| `recent-results.sh` | Completed matches |
| `ipl.sh` | IPL-specific data |
| `search-match.sh` | Search by team/tournament |
| `cricket-alert.sh` | Automated match alerts |

## License

MIT
