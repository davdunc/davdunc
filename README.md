# David Duncan

I believe that open-source infrastructure and systematic thinking can solve real problems — from making Linux cloud images better to making a trader more disciplined. I work at the intersection of cloud-native infrastructure, AI-assisted automation, and personal performance systems.

By day, I'm a Partner Solutions Architect at AWS focused on open-source and Linux. By early morning, I'm a momentum day trader building systems to replace intuition with data. Both are the same mission: build infrastructure that makes the next decision better than the last one.

## What I'm Building

- **[Falcon](https://github.com/davdunc/falcon)** — Trading automation platform bridging DAS Trader, IBKR, and cloud-native infrastructure (Podman, Quadlets, Lambda, Step Functions)
- **[falcon-stats](https://github.com/davdunc/falcon-stats)** — Trading discipline system: round-trip identification, R-multiple analysis, statistical covariance, and honest self-assessment from 1,254 real trades
- **[PAI Framework](https://github.com/davdunc/pai-framework)** — My fork of [Daniel Miessler](https://danielmiessler.com)'s [Personal AI Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure), rebuilt for systematic trading and Fedora Cloud work
- **[davdunc-plugins](https://github.com/davdunc/davdunc-plugins)** — Claude Code plugins for equities trading: market data from Massive.com/Polygon and watchlist generation via Finviz
- **Fedora Cloud SIG** — Contributing to bootable container images and cloud image defaults for the [Fedora Project](https://fedoraproject.org)

## The Trading Thesis

I'm a winning trader with a losing habit. 51% green days, but my red days are 2.5x my green days. The fix isn't better stock picks — it's better discipline. So I built a complete data pipeline:

```
DAS Trader CSV → falcon-stats → DynamoDB → Notion + Slack + Blog
                                    ↑
                         1,254 round-trips
                         Statistical covariance (z-scores)
                         Discipline scoring (process, not P&L)
                         Ticker restriction lists (data-backed)
```

Philosophy: **Trade the setup, not the P&L.** Order flow first, price action second, and never let the dollar amount on screen drive the decision. [Read more →](https://www.davidduncan.org/falcon-stats-trading-discipline.html)

## Projects

| Project | Description |
|---------|-------------|
| [falcon-stats](https://github.com/davdunc/falcon-stats) | Trading statistics engine with DynamoDB, Cobra/DAS parsers, trade calculator, Fedora container |
| [falcon](https://github.com/davdunc/falcon) | AWS execution platform: Lambda + Step Functions for automated morning game plans |
| [pai-framework](https://github.com/davdunc/pai-framework) | PAI fork: 7 skills, 22 hooks, Algorithm v3.7.0, TELOS integration |
| [davdunc-plugins](https://github.com/davdunc/davdunc-plugins) | Claude Code trading plugins: Polygon OHLCV, Finviz screening, Camarilla pivots |
| [das-cmd-test](https://github.com/davdunc/das-cmd-test) | DAS Trader CMD API async Python client |
| [eponymous_blog](https://github.com/davdunc/eponymous_blog) | Blog content for [davidduncan.org](https://www.davidduncan.org) |

## Recent Writing

- [falcon-stats: A Trading Discipline System Built on PAI](https://www.davidduncan.org/falcon-stats-trading-discipline.html)
- [Building a Bookmap-Style CVD Indicator with Claude Code and Python](https://www.davidduncan.org/cvd-indicator-bookmap.html)
- [PAI Framework: How I Rebuilt a Personal AI Infrastructure](https://www.davidduncan.org/pai-framework.html)
- [Building Claude Code Plugins for Trading](https://blog.davidduncan.org/building-claude-code-plugins-for-trading.html)

## Platform

I work on Fedora Linux, not macOS. My infrastructure runs on Podman, not Docker. Containers use `registry.fedoraproject.org/fedora:44` as the base image. I believe in open-source tooling and Linux-native infrastructure — and I prove it by running my trading systems on the same OS patterns I contribute to at Fedora Cloud SIG.

## Connect

- **Blog:** [davidduncan.org](https://www.davidduncan.org) · [blog.davidduncan.org](https://blog.davidduncan.org)
- **Bluesky:** [@davdunc](https://bsky.app/profile/davdunc)
- **X:** [@davdunc](https://x.com/davdunc)
- **Location:** Austin, TX

---

*Built with [Daniel Miessler](https://danielmiessler.com)'s [PAI](https://github.com/danielmiessler/Personal_AI_Infrastructure) and [TELOS](https://danielmiessler.com/telos/) frameworks. Grateful for the architecture that made this possible.*
