# 🏀 NBA Awards Predictor (2024–25 Season)

This project builds a comprehensive, data-driven system to predict the winners of major NBA awards for the 2024–25 season using real player stats and advanced tracking data.

---

## 🧠 Awards Modeled

- 🏆 **Most Valuable Player (MVP)**
- 🛡️ **Defensive Player of the Year (DPOY)**
- 🌱 **Rookie of the Year (ROY)**
- 📈 **Most Improved Player (MIP)**
- 🪑 **Sixth Man of the Year (6MOY)**
- 🧊 **Clutch Player of the Year**

---

## 🔍 Data Sources

- [`nba_api`](https://github.com/swar/nba_api) — live player stats & tracking data
- Player box scores, tracking data, clutch splits, and draft history

---

## 🛠️ Methods Used

- Python (Pandas, Matplotlib, Seaborn)
- Custom scoring models per award based on:
  - Per-game stats
  - Team success
  - Defensive tracking (opponent FG%)
  - Clutch-time performance
- 65-game eligibility filtering (NBA's new awards rule)

---

## 🎨 Visualizations

Each award includes a top 10 leaderboard visualized with:
- Horizontal bar charts
- Custom team color palettes
- Embedded **NBA team logos**

---

## 📊  Output

| Award | Predicted Winner |
|-------|------------------|
| MVP   | Nikola Jokic     |
| DPOY  | Dyson Daniels    |
| ROY   | Stephon Castle   |
| MIP   | Dyson Daniels    |
| 6MOY  | Payton Pritchard |
| Clutch| Jalen Brunson    |


---

## 🚀 Future Ideas

- Interactive Streamlit dashboard
- Forecasting next year’s awards based on historical trends
- Integration with team metrics (defensive rating, win shares)

---

## 🧾 How to Run

```bash
# install dependencies
pip install nba_api matplotlib seaborn scikit-learn

# run notebook
jupyter notebook NBA_Awards_Predictions_2025.ipynb
