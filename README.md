### Hi, I'm Henry 👋

I build tools and data pipelines around **Deadlock**, a hero shooter by Valve.

#### What I'm working on

| Project | What it does |
|---------|--------------|
| **[deadlock-hero-stats](https://github.com/2025henryzhang-ops/deadlock-hero-stats)** | Pulls win/pick rates for all 43 heroes from the public Deadlock API and emits a normalized JSON snapshot |
| **[GameGoldLab](https://gamegoldlab.com)** | Weekly meta reports, hero guides, builds and tier lists built on that data |

#### Live data

- **[Weekly meta report](https://gamegoldlab.com/data/report)** — top/bottom heroes by real ranked win rate
- **[Hero stats](https://gamegoldlab.com/hero-stats)** — per-hero win rate, pick rate and tier
- **[Tier list](https://gamegoldlab.com/tier-list)** — updated weekly
- **[Hero guides](https://gamegoldlab.com/heroes)** — abilities, builds, matchups and counters

#### Method

Win rates come from real ranked matches over a rolling 7-day window
(roughly 500k–1.2M matches per hero, 26M total). No sampling estimates.

---

<sub>Data source: [deadlock-api.com](https://api.deadlock-api.com) · Reports: [gamegoldlab.com](https://gamegoldlab.com)</sub>
