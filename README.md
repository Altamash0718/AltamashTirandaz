# 🏏 Player Performance Predictor - IPL Data Science Project

This project predicts the expected **runs** a selected **batsman** might score in a specific match scenario using machine learning models trained on IPL data. It also displays enhanced statistics for both batting and bowling performances.

## 📦 Project Features

- Load and merge IPL deliveries and matches datasets.
- Generate batsman-level performance statistics.
- Compute and display career stats including:
  - Total runs
  - Average
  - Strike rate
  - Last 5 matches performance
- Train three machine learning models:
  - Random Forest Regressor (with hyperparameter tuning)
  - Support Vector Regressor (SVR)
  - XGBoost Regressor
- Predict expected runs for a selected player based on:
  - Batting team
  - Bowling team
  - Venue
  - Inning
  - Player's career average
- Show enhanced career statistics including bowling metrics (wickets, economy, etc.)

---

## 📁 Dataset Requirements

Place the following CSV files in the `/content/` directory (or update the paths in code):

- `deliveries.csv` – Ball-by-ball delivery data.
- `matches.csv` – Match-level information including venue.

These datasets are publicly available on [Kaggle - IPL Dataset](https://www.kaggle.com/datasets).

---

## 🛠️ Setup & Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/ipl-performance-predictor.git
   cd ipl-performance-predictor
