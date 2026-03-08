# Trader Performance vs Market Sentiment

## Objective:
Analyze how market sentiment (Fear/Greed) relates to trader behavior and performance on Hyperliquid. Your goal is to uncover patterns that could inform smarter trading strategies.

## Setup Instructions:
1. Prerequisites
Ensure you have Python 3.8+ installed on your system.

2. Clone the Repository

```
git clone https://github.com/pmalhi1/Data-Science-Projects-Personal.git
cd Trader Behavior Insights
```

3. Install Dependencies
Install the required data science libraries using pip:

`pip install pandas matplotlib seaborn numpy`

4. Data Preparation
Place your data files in the "Trader Behavior Insights" directory. Download the files from these links:

- Bitcoin Market Sentiment (Fear/Greed)
Columns: Date, Classification (Fear / Greed)
Link: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
        
- Historical Trader Data (Hyperliquid)
Includes fields like: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.
Link: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Save these data files as fear_greed_index.csv and historical_data.csv

## How to Run:
Run the notebook in following path:

Data-Science-Projects-Personal/Trader Behavior Insights/trader_behaviour_insights.ipynb
