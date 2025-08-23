# Sports Analytics Portfolio

A collection of sports analytics projects exploring players, teams, and title-winning seasons. Each project includes reproducible notebooks, clear methodology, and exportable visuals for articles and presentations.

> If you use or adapt anything here, a ⭐ on the repo is appreciated!

---

## 📚 Projects (current)

| # | Project                                                     | Focus                                                          | Status      |
| - | ----------------------------------------------------------- | -------------------------------------------------------------- | ----------- |
| 1 | **Aitana Bonmatí — 2023 Season & FIFA Women’s World Cup**   | Creative playmaking, shot creation, custom xT/xG               | Complete    |
| 2 | **Bayer Leverkusen — Bundesliga 2023/24 (Title Winners)**   | Team style & phases of play, press/possess/transition analysis | Complete    |
| 3 | **Leicester City — Premier League 2015/16 (Title Winners)** | Underdog tactics, chance quality, player profiles (Vardy)      | Complete    |


**Data notes**

* Some projects use **public/open datasets** (e.g., StatsBomb Open Data via `statsbombpy`) and others use **publicly available match data** (documented inside the notebooks).
* For large/open datasets: first run the corresponding data-loading cell in each notebook; it will download/cache data where allowed.
* Private/paid data (if any) is **not** committed. You’ll see clear placeholders in notebooks on how to connect your own source.

---

## 🔬 Methodology Overview

### 1) Aitana Bonmatí — 2023 Season & World Cup

**Goal:** Explain *why* Aitana won major individual awards using data.

* **Key analyses:**

  * Key passes & passes into the box (maps)
  * **Custom xT** (expected threat) model for progressive value
  * Shot map with **xG**; open-play chain contributions (xGChain/xGBuildup)
  * Supporting stats: xA, SCA/90, deep completions
* **Outputs:** visual dashboards (pitch maps, radars), concise narratives for articles.

---

### 2) Bayer Leverkusen — Bundesliga 2023/24 (Title Winners)

**Goal:** Break down Xabi Alonso’s side—*how* they controlled games and sustained results.

* **Key analyses:**

  * Team style profile across phases (build-up, final third, transitions)
  * Passing networks & average position maps
  * Shot volume/quality trends; chance creation web
  * Late-goal patterns & game-state effects
* **Outputs:** team radars, passing networks, xG timelines, possession thirds.

---

### 3) Leicester City — Premier League 2015/16 (Title Winners)

**Goal:** Quantify and visualize the 5000–1 miracle season.

* **Key analyses:**

  * Defensive compactness vs. direct attacks
  * Shot quality vs. shot volume trade-offs
  * **Player profile: Jamie Vardy**—movement maps, shot map, finishing profile
  * Set-pieces & transition opportunities
* **Outputs:** match and season-level dashboards; player-focused visuals.

---

## 📄 Licensing & Data Usage

* **Code:** Choose a license (e.g., MIT) and place it in `LICENSE`.
* **Data:** Respect provider terms. *StatsBomb Open Data*, where used, is released under **CC BY-NC 4.0**. Cite appropriately and do not use for commercial purposes. Other public sources retain their original licenses—see notebook headers for source notes.

---

## Contributions & Feedback

Issues and PRs are welcome—especially around:

* Additional visuals (radars, sequence networks, expected threat variants)
* Performance optimizations for large match sets
* Clearer storytelling templates for articles


* **Author:** Rishiraj Sinharay
If you build on these, I’d love to see your work!
