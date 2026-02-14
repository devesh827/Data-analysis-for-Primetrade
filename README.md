# Data-analysis-for-Primetrade
# Trader Performance vs Market Sentiment

## Overview
This project analyzes how Bitcoin market sentiment (Fear & Greed Index)
impacts trader behavior and performance on Hyperliquid.

## Datasets
- Trader Historical Data (Hyperliquid)
- Bitcoin Fear & Greed Index

## Methodology
1. Converted Unix timestamps to datetime and aligned data at daily level
2. Merged trader data with sentiment data using date
3. Created daily trader metrics:
   - PnL
   - Win rate
   - Trade frequency
   - Average trade size
   - Long/Short ratio
4. Compared performance across Fear vs Greed regimes
5. Segmented traders using quantile-based binning

## Key Insights
- Traders perform better during Greed days
- Fear days lead to lower activity and smaller positions
- Consistent traders outperform across all regimes

## Strategy Recommendations
- Reduce leverage and exposure during Fear periods
- Increase activity selectively during Greed periods

## How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib
2. Run the notebook:
   Trader Performance vs Market Sentiment.ipynb
