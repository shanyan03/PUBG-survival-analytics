# PUBG Survival Analytics: From Raw Data to Playable Insights

**One-liner:** First-year data science project turning two messy PUBG datasets into clear tips for beginners-party size, safer early-game landings, weapons, assisting teammates, movement choices, and bluezone timing.

## What’s here
- `data/final_kill_match_stats.csv`
- `data/final_agg_match_stats.csv`
- `reports/Data Pre-processing.html` – how the raw data was cleaned and reduced
- `reports/Data Analysis and Visualisation.html` – analysis & charts (KDE maps, etc.)
- ## Notebooks

You can view the notebooks directly on GitHub:

- **Data Pre-processing** → [`scripts/Data Pre-processing.ipynb`](scripts/Data%20Pre-processing.ipynb)  
  Steps to clean, reduce, and standardize the raw PUBG data (Erangel focus).

- **Data Analysis & Visualisation** → [`scripts/Data Analysis and Visualisation.ipynb`](scripts/Data%20Analysis%20and%20Visualisation.ipynb)  
  Exploratory analysis and charts (KDE maps, party size vs win rate, weapons, bluezone).

## Highlights
- Focus on **Erangel** for consistent comparisons  
- Practical cleaning: reduction, feature selection, date/unit fixes, missing values  
- Visual insights that translate to simple survival tips

## Getting started
Download this repo and open the HTML reports in your browser for a guided tour of the preprocessing and analysis.

## Results (visuals)
<p align="center">
  <img src="figures/final_bluezone.jpg" alt="Bluezone progression" width="48%">
  <img src="figures/most_dangerous_locations.jpg" alt="Probability to win" width="48%">
</p>

<p align="center">
  <img src="figures/prob_to_win.jpg" alt="Bluezone progression" width="48%">
  <img src="figures/top_15_weapons.jpg" alt="Probability to win" width="55%">
</p>

## Author
Lee Shan Yan 

