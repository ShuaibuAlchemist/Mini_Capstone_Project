Mini Capstone Project

📌 Project Overview

This project is part of my data science learning journey, focused on analyzing blockchain data. It investigates the relationship between whale transactions (transfers exceeding 100,000) and price movements of selected cryptocurrencies. It aims to determine whether spikes in whale activity correlate with or precede significant market volatility. The analysis combines on-chain data and market price data using Dune, CoinGecko, and Python-based data analytics.

🧠 Key Questions

- Do whale transaction spikes align with or predict price volatility?
- Is there a directional pattern between large transfers and market trends?

🔍 Workflow Summary

1. Data Collection
   - Market Price Data: via CoinGecko API (/market_chart) for historical prices (OHLCV).
   - Whale Transactions: via Dune API or dashboards filtered for transfers >100K.

2. Data Wrangling
   - Merge price and transaction data on timestamps.
   - Feature engineering: price % change, whale transfer volume, whale spike flags.

3. Exploratory Analysis
   - Time series plots comparing whale activity vs. price.
   - Scatterplots of transfer volume vs. price change.
   - Correlation and rolling window analysis.

   🧰 Tools & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- CoinGecko API, Dune Analytics

🚀 How to Run

1. Clone this repo
2. Add API keys to .env file
3. Install dependencies from requirements.txt
4. Run the Jupyter notebooks to explore insights

👤 Author

Muhammad Shuaibu  
[GitHub](https://github.com/ShuaibuAlchemist)
