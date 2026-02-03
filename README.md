# Trader Behavior vs Market Sentiment (Fear vs Greed)

## Objective
The objective of this project is to analyze how trader performance and behavior differ under
different market sentiment conditions (Fear vs Greed) using historical trading data.

## Datasets Used
- Bitcoin Fear & Greed Index (Daily market sentiment classification)
- Historical trader data from Hyperliquid (trade-level information)

## Analysis Performed
- Cleaned and aligned trader data with daily market sentiment
- Analyzed PnL distribution across Fear and Greed days
- Compared average PnL between Fear and Greed
- Compared trade activity (number of trades) across sentiment regimes

## Key Insights
- Fear days show higher volatility with more extreme profit and loss outcomes
- Median PnL remains close to zero for both Fear and Greed periods
- Trade activity is higher during Fear periods compared to Greed periods

## Outputs
All visualizations generated during the analysis are available in the `outputs/` folder:
- PnL distribution (Fear vs Greed)
- Average PnL comparison
- Trade count comparison

## How to Run
Open `notebook_1.ipynb` and run all cells sequentially to reproduce the analysis.

## Author
Jwel Aktar
