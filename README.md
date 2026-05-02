### Hi, I'm David Duncan

I believe sustainable independence comes from owning two things: the
infrastructure you depend on, and the data you make decisions from. Most people
rent both. I'd rather build them.

By day I'm a Partner Solutions Architect at AWS, working on open source and
Linux. In the Fedora Cloud SIG I help ship the cloud images and bootable
containers that other people's infrastructure runs on. Before the market opens
I'm a momentum day trader, building the systems to replace intuition with data
— and to fund the open-source work without depending on employer alignment.

Both halves are the same project: **build infrastructure that makes the next
decision better than the last one.**

---

## Mission

**M1 — Community science for cloud-native Linux.** Harness collective
problem-solving and shared intelligence to make cloud-native Linux
infrastructure accessible, reliable, and community-driven.

**M2 — Open-source financial and AI sovereignty.** Build open-source financial
and AI systems on community-driven Linux infrastructure that give individuals
sovereignty over their own data, tools, and economic reasoning.

---

## What I'm Working Toward

**Fedora & open source**
- Speak at Fedora conferences (Flock, DevConf) about cloud images and bootable
  containers — practical demos, not abstractions
- Ship improved defaults in Fedora Cloud images for an upcoming release
- Grow the Fedora Cloud SIG contributor base — recruit and onboard contributors
  who stick around

**Trading & financial sovereignty**
- Become a consistently profitable systematic day trader
- Follow a structured morning game plan every trading day
- Graduate high-conviction trades from sim to live with proper sizing
- Transition from discretionary to systematic / algorithmic execution
- Ship Falcon end-to-end so the trading pipeline runs without me babysitting it

---

## What I'm Building

**[Falcon](https://github.com/TradingAsBuddies)** is the trading-automation
ecosystem — Lambda + Step Functions for morning game plans, DAS Trader and IBKR
integration, and a Fedora-native execution stack on Podman + Quadlets. Built in
public under the [TradingAsBuddies](https://github.com/TradingAsBuddies)
organization, where my trading strategies and tools live.

**[falcon-stats](https://github.com/davdunc/falcon-stats)** is the discipline
layer — round-trip identification, R-multiple analysis, statistical covariance,
and an honest self-assessment built from 1,254 of my own trades. The thesis: if
you can't measure your behavior, you can't fix it.

**[PAI Framework](https://github.com/davdunc/pai-framework)** is my fork of
[Daniel Miessler](https://danielmiessler.com)'s [Personal AI
Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure),
rebuilt around systematic trading and Fedora Cloud work — Algorithm v3.7.0,
TELOS-driven goal context, and trading-focused skills.

**[davdunc-plugins](https://github.com/davdunc/davdunc-plugins)** is a small
collection of Claude Code plugins for equities work — Polygon OHLCV, Finviz
screening, Camarilla pivot calculation.

**Fedora Cloud SIG** is the open-source contribution thread — bootable
container images and cloud image defaults for the
[Fedora Project](https://fedoraproject.org).

---

## The Trading Thesis

I'm a winning trader with a losing habit. 51% green days, but my red days are
2.5x my green days. The fix isn't better stock picks — it's better discipline.
So I built a complete data pipeline:

```
DAS Trader CSV → falcon-stats → DynamoDB → Notion + Slack + Blog
                                    ↑
                         1,254 round-trips
                         Statistical covariance (z-scores)
                         Discipline scoring (process, not P&L)
                         Ticker restriction lists (data-backed)
```

Philosophy: **Trade the setup, not the P&L.** Order flow first, price action
second, and never let the dollar amount on screen drive the decision.
[Read more →](https://www.davidduncan.org/falcon-stats-trading-discipline.html)

---

## Projects

| Project | Description |
|---------|-------------|
| [TradingAsBuddies](https://github.com/TradingAsBuddies) | Org where the Falcon ecosystem lives — `falcon-core`, `falcon-trader`, `falcon-deploy`, `falcon-operator`, `falcon-screener`, `falcon-messenger`, `falcon-gateway` |
| [falcon-stats](https://github.com/davdunc/falcon-stats) | Trading statistics engine: DynamoDB, Cobra/DAS parsers, trade calculator, Fedora container |
| [pai-framework](https://github.com/davdunc/pai-framework) | PAI fork: skills, hooks, Algorithm v3.7.0, TELOS integration |
| [davdunc-plugins](https://github.com/davdunc/davdunc-plugins) | Claude Code trading plugins: Polygon OHLCV, Finviz screening, Camarilla pivots |
| [das-cmd-test](https://github.com/davdunc/das-cmd-test) | DAS Trader CMD API async Python client |
| [eponymous_blog](https://github.com/davdunc/eponymous_blog) | Blog content for [davidduncan.org](https://www.davidduncan.org) |

---

## Recent Writing

- [falcon-stats: A Trading Discipline System Built on PAI](https://www.davidduncan.org/falcon-stats-trading-discipline.html)
- [Building a Bookmap-Style CVD Indicator with Claude Code and Python](https://www.davidduncan.org/cvd-indicator-bookmap.html)
- [PAI Framework: How I Rebuilt a Personal AI Infrastructure](https://www.davidduncan.org/pai-framework.html)
- [Building Claude Code Plugins for Trading](https://blog.davidduncan.org/2026/04/05/building-claude-code-plugins-for-trading/)

---

## Platform

I work on Fedora Linux, not macOS. My infrastructure runs on Podman, not
Docker. Containers use `registry.fedoraproject.org/fedora:44` as the base
image. I believe in open-source tooling and Linux-native infrastructure — and
I prove it by running my trading systems on the same OS patterns I contribute
to at Fedora Cloud SIG.

---

## Connect

[Blog](https://www.davidduncan.org) ・ [Newsletter](https://blog.davidduncan.org) ・ [Bluesky](https://bsky.app/profile/davdunc.bsky.social) ・ [X](https://x.com/davdunc) ・ [All Repos](https://github.com/davdunc?tab=repositories) ・ Austin, TX

---

*Built on [Daniel Miessler](https://danielmiessler.com)'s [PAI](https://github.com/danielmiessler/Personal_AI_Infrastructure) and [TELOS](https://danielmiessler.com/telos/) frameworks. Grateful for the architecture that made this possible.*
