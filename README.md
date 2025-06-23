# trader_sentiment_analysis
Objective:
This project analyzes how market sentiment, measured by the Bitcoin Fear and Greed Index, impacts trader behavior and performance on the Hyperliquid platform. The goal is to identify behavioral trends, measure performance variations, and explore whether market emotion can be used as a signal for trading strategies.
Datasets Used:
1.Trader Data (historical_data.csv)
*Contains individual trade logs including account info, side (Buy/Sell), execution price, position size, closed PnL, and timestamp.
*Source: Provided Hyperliquid trade logs.
2.Fear & Greed Index (fear_greed_index.csv)
*Contains daily sentiment score and classification (Extreme Fear to Extreme Greed) from a leading crypto sentiment index.
*Source: Alternative.me
Key Analyses Performed:
Daily Aggregation of Trader Metrics:
*Average PnL, Total PnL, Standard Deviation (volatility)
*Long/Short ratio (Buy proportion)
*Number of unique traders per day
Sentiment Mapping:
*Binary: Fear (0) vs Greed (1)
*5-Level: Extreme Fear → Extreme Greed (0–4)
EDA & Visualizations:
*Boxplots comparing performance across sentiment levels
*Correlation heatmaps
*Linear regression and Spearman correlation
Statistical Tests:
*T-test: Is avg_PnL significantly different between Fear and Greed?
*Correlation: Relationship strength between sentiment and performance
Machine Learning (Bonus):
*Random Forest classifier to predict sentiment class based on trading behavior
Sample Insights:
*Trader PnL tends to increase during Greed states and drop during Fear.
*Long positions are more common in Greed-driven markets.
*Market sentiment shows a moderate correlation with average daily performance.
*A basic model can classify market sentiment with decent accuracy using PnL and activity metrics.
Tools Used:
*Python, Pandas, NumPy
*Matplotlib, Seaborn
*Scikit-learn
*Jupyter Notebook




