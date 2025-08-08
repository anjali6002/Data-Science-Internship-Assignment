# Data-Science-Internship-Assignment

-----

### Trader Behavior Insights Project - Anjali
#### Executive Summary

This project addresses a data science assignment to explore the relationship between trader performance and market sentiment. By analyzing two distinct datasets—historical trader data from Hyperliquid and the Bitcoin Fear & Greed Index—I aimed to uncover patterns that could inform smarter trading strategies.

The key finding is a surprising correlation: traders in this dataset were, on average, most profitable during periods of **Extreme Greed**, and least profitable during **Neutral** market conditions. This suggests that for this group, heightened market emotions did not lead to poor performance, but rather presented opportunities.

-----

#### Methodology

1.  **Data Acquisition and Cleaning:** The two datasets were loaded and inspected for any issues. The `Timestamp IST` and `date` columns were converted to a consistent datetime format to enable accurate merging.
2.  **Data Merging:** The historical trader data and the Fear & Greed Index data were merged into a single, comprehensive DataFrame using the `date` column as a key.
3.  **Exploratory Data Analysis (EDA):** The combined dataset was used to calculate key statistics and create visualizations to identify patterns. The primary focus was on analyzing the average `Closed PnL` (Profit and Loss) in relation to the `classification` (sentiment).

*Note: Due to GitHub's file size limits, the original and merged CSV files are provided in compressed format (`.zip`). Please decompress these files to access the data.*

-----

#### Key Findings and Insights

**Overall Trader Performance:**
The traders in this dataset were generally profitable, with an **overall average `Closed PnL` of $48.55**.

**Trading Activity by Sentiment:**
The highest number of trades occurred during periods of **Fear**, followed by **Greed**. This indicates that traders are most active during times of moderate market uncertainty and optimism.

**Performance by Sentiment:**
A clear relationship was found between market sentiment and average profitability:

  * **Most Profitable:** Trades during **Extreme Greed** periods yielded the highest average PnL at **$67.89**.
  * **Second Most Profitable:** Periods of **Fear** were also highly profitable, with an average PnL of **$54.29**.
  * **Least Profitable:** The lowest performance was observed during **Neutral** and **Extreme Fear** periods, with average PnLs of $34.31 and $34.54, respectively.

-----

#### Conclusion and Next Steps

This project successfully demonstrates that for this cohort of traders, profitability is directly linked to market sentiment. The data suggests that traders performed best when the market was at its most bullish, contradicting the common notion that greed leads to poor decision-making.

For future work, a deeper analysis could explore the impact of leverage on profitability within different sentiment categories or analyze the behavior of individual accounts to identify successful trading patterns.
