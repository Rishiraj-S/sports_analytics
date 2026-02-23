# Sports Analytics Portfolio

A collection of sports analytics projects covering football (soccer) and cricket. Each project includes reproducible notebooks, clear methodology, and exportable visuals for articles and presentations.

> If you find this useful, a star on the repo is appreciated!

---

## Repository Structure

```
sports_analytics/
├── football/
│   ├── aitana_bonmati/               # FIFA Women's World Cup 2023 + EURO 2025
│   ├── bayer_leverkusen_2023_24/     # Bundesliga 2023/24 unbeaten title season
│   ├── leicester_city_2015_16/       # Premier League 2015/16 miracle season
│   └── macclesfield_vs_crystal_palace/  # FA Cup single-match analysis
├── cricket/
│   └── arshdeep_singh_t20.ipynb     # T20 bowling analysis (IPL + internationals)
├── assets/                           # Portfolio visualisations
├── requirements.txt
└── .gitignore
```

---

## Projects

### Football

| # | Project | Focus | Status |
|---|---------|-------|--------|
| 1 | **Aitana Bonmatí — Women's World Cup 2023 & EURO 2025** | Creative playmaking, xT/xG, shot creation | Complete |
| 2 | **Bayer Leverkusen — Bundesliga 2023/24** | Team style, phases of play, late-game patterns | Complete |
| 3 | **Leicester City — Premier League 2015/16** | Underdog tactics, chance quality, player profiles | Complete |
| 4 | **Macclesfield FC vs Crystal Palace — FA Cup (2-1)** | Single-match event data analysis | Complete |

### Cricket

| # | Project | Focus | Status |
|---|---------|-------|--------|
| 1 | **Arshdeep Singh — T20 Bowling Analysis** | Phase-wise economy, dot-ball %, IPL vs T20I | Complete |

---

## Methodology

### Aitana Bonmatí — Women's World Cup 2023 & EURO 2025

**Goal:** Explain why Aitana won major individual awards using data.

- Key passes, passes into the box (pitch maps)
- Custom xT (expected threat) model for progressive value
- Shot map with xG; open-play chain contributions (xGChain / xGBuildup)
- Supporting stats: xA, SCA/90, deep completions
- Outputs: visual dashboards (pitch maps, radars), article narratives

### Bayer Leverkusen — Bundesliga 2023/24

**Goal:** Break down Xabi Alonso's side — how they controlled games and sustained results.

- Team style profile across phases (build-up, final third, transitions)
- Passing networks and average position maps
- Shot volume/quality trends; chance creation web
- Late-goal patterns and game-state effects
- Outputs: team radars, passing networks, xG timelines, possession thirds

### Leicester City — Premier League 2015/16

**Goal:** Quantify and visualise the 5000-to-1 miracle season.

- Defensive compactness vs. direct attacks
- Shot quality vs. shot volume trade-offs
- Player profile: Jamie Vardy — movement maps, shot map, finishing profile
- Set-pieces and transition opportunities
- Outputs: match- and season-level dashboards; player-focused visuals

### Macclesfield vs Crystal Palace — FA Cup

**Goal:** Single-match tactical breakdown using Opta event data.

- Event volume and category breakdown by team
- Possession and passing efficiency
- Defensive and attacking action comparison

### Arshdeep Singh — T20 Bowling Analysis

**Goal:** Quantify Arshdeep's bowling across formats and phases.

- Phase-wise economy (powerplay, middle, death)
- Dot-ball percentage by phase
- IPL vs T20 international split across 5,800+ match files

---

## Setup

```bash
pip install -r requirements.txt
```

Data notes:
- Football projects use **StatsBomb open data** via `statsbombpy` — run the data-loading cell in each notebook to fetch it.
- Cricket data (JSON files) is bundled in `cricket/ipl_json/` and `cricket/t20s_json/`.
- Opta data (`football/macclesfield_vs_crystal_palace/`) is included in the repository.

---

## Licensing & Data Usage

- **Code:** MIT License — see `LICENSE`.
- **StatsBomb open data:** CC BY-NC 4.0 — cite appropriately and do not use commercially.
- **Cricket match data:** sourced from [Cricsheet](https://cricsheet.org/) (CC BY-SA 4.0).
- Other public sources retain their original licenses — see notebook headers for details.

---

## Author

**Rishiraj Sinharay** — [@rishiraj1998.rs on Medium](https://medium.com/@rishiraj1998.rs)

Contributions, issues, and PRs are welcome — especially around additional visuals, performance optimisations, and clearer storytelling templates.
