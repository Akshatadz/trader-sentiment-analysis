# trader-sentiment-analysis
Data science internship task – Trader performance vs Bitcoin sentiment
# Trader Sentiment Analysis — Primetrade.ai Assignment

**Author:** Akshata Z.  
**Task:** Analyze relationship between trader performance and Bitcoin market sentiment (Fear & Greed).

## Datasets
- Historical trader data (Hyperliquid) — `historical_data.csv`
- Bitcoin Fear & Greed Index — `fear_greed_index.csv`

## Steps performed
1. Loaded and cleaned both datasets; standardized date columns and merged on `Date`.
2. Calculated average **Closed PnL** for each sentiment class (Extreme Fear, Fear, Neutral, Greed, Extreme Greed).
3. Visualized distribution of PnL by sentiment using a boxplot.
4. Ranked accounts by average PnL under each sentiment to identify top performers and contrarians.

## Key findings (high-level)
- **Extreme Greed** and **Fear** show higher average PnL, suggesting extremes create more trading opportunities.
- **Neutral** periods show tighter PnL distributions (lower volatility).
- A small set of accounts are **consistent high-performers** in specific sentiment regimes (momentum vs contrarian behavior).

## How to run
1. Open `data_science_internship.ipynb` in Jupyter Notebook.
2. Ensure `historical_data.csv` and `fear_greed_index.csv` are in the same folder.
3. Run the notebook cells from top-to-bottom. Required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`.

Akshata Z. — 
akshata17003@gmail.com

