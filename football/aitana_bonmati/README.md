# Aitana Bonmatí — Data-Driven Analysis (Women's World Cup 2023 & EURO 2025)

Data-driven analysis explaining why Aitana Bonmatí was the standout player of both tournaments.

## Notebooks

| Notebook | Description |
|----------|-------------|
| `worldcup_2023.ipynb` | Full Women's World Cup 2023 analysis |
| `euro_2025.ipynb` | EURO 2025 analysis |

## Key Analyses

- Touch heatmap and pass network
- Key passes, penalty box entries, and progressive pass flows
- Custom xT (expected threat) model built with scikit-learn
- xGChain and xGBuildup flow analysis
- Defensive actions and pressure heatmap

## Data

| File | Description |
|------|-------------|
| `xT_Grid.csv` | Pre-computed expected threat grid used by both notebooks |

StatsBomb open Women's World Cup 2023 event data is fetched at runtime via `statsbombpy`.

## Tech Stack

- Python, pandas, numpy
- statsbombpy (StatsBomb open data)
- mplsoccer, matplotlib, seaborn
- scikit-learn, networkx

## Articles

- [Inside the Numbers: How Aitana Bonmatí Dominated the 2023 FIFA World Cup](https://medium.com/@rishiraj1998.rs/inside-the-numbers-how-aitana-bonmat%C3%AD-dominated-the-2023-fifa-world-cup-7c4796e52b2d)

## Credits

- [StatsBomb](https://statsbomb.com/) for public WWC 2023 event data
- [mplsoccer](https://mplsoccer.readthedocs.io/) for football pitch visualisation tools
