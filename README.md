# ⚽ European Soccer Leagues Database Analysis – 2024/2025 Season

This project performs an **exploratory and statistical analysis of players in European soccer leagues for the 2024/2025 season**, using Python and data science libraries. The goal is to identify offensive and defensive performance patterns, evaluate leagues, and build the **“Dream Team”** based on performance metrics.

---

## 📁 Repository Sctructure

```
├── futebol data analysis.ipynb     # Main notebook with analysis and vizualization
├── players_data_light-2024_2025.csv # Season player database
```

---

## 🧩 Libraries
* **Pandas** – data processing and analysis
* **Matplotlib / Seaborn** – statistical vizualization
---


## 📊 Key Analysis

| Analysis                     | Description                                                          | Key Metrics                                         |
| ---------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Top Offensive Players**  | Best performanced players in offensive actions. | Goals + assists (“G+A”).     |
| **Top Defensive Players** | Best performanced players in defensive actions.                          | Tackles & Interceptions ("Tkl+Int")  |
| **Best Leagues** | Compare leagues by offensive and defensive averages.                          | Best defenders and forwards.
| **Best Goalkeepers**        | Analyzes goalkeepers based on saves. | Saves per game. |
| **Dream Team**               | Assembling the ideal team by combining the best players, without league restrictions. | Overall ranking weighted by performance and impact.           |

---
# ⚔️ Top 10 Offensive Players (G+A)
![Top 10 Offensive Players](/images/top10ofensivos.png)

# 🛡️ Top 10 Jogadores Defensivos (Tkl+Int)
![Top 10 Defensive Players](/images/top10defensivos.png)

# 🧤 Top Goalkeepers (Saves)
![Top Goalkeepers](/images/melhores_goleiros_por_liga.png)

# ⚽️ Dream Team (FORMATION 3-5-2)
![Dream Team](/images/dream_team.png)

---

## 💡 Future Extensions

* Integration with historical data (last 5 seasons)
* Analysis of player performance evolution
* Creation of interactive dashboard (Streamlit or Power BI)

