# Trader Behavior & Market Sentiment Analysis

## Overview
This project explores the relationship between Bitcoin market sentiment and trader behavior using two key datasets:

1. **Bitcoin Market Sentiment Dataset** – Fear/Greed classifications over time.  
2. **Historical Trader Data (Hyperliquid)** – Trade details including account, trade size, execution price, PnL, and more.  

The objective is to analyze how trading behavior (profitability, risk exposure, trade volume, leverage) aligns with market sentiment and uncover insights that could inform smarter trading strategies.  


## Folder Structure
```

ds_Sanghavai/
├── notebook_1.ipynb       
├── notebook_2.ipynb       
├── csv_files/             
│   ├── historical_data.csv
│   └── fear_greed_index.csv
├── outputs/               
│   ├── pnl_distribution.png
│   ├── trade_size.png
│   └── trade_counts.png
├── ds_report.pdf          
└── README.md              

```



## Methodology
1. Loaded datasets in Python using Pandas.  
2. Standardized timestamps and merged datasets by trade date.  
3. Conducted exploratory data analysis (EDA) on:
   - Profitability (`Closed PnL`)
   - Trade size (`Size USD`)
   - Number of trades per sentiment  
4. Visualized results using boxplots and bar charts.  
5. Derived actionable insights based on sentiment-driven trading behavior.  


## Key Insights
- **Emotional sentiment drives trading activity and volatility.**  
- **Fear periods** see the highest number of trades and largest swings in PnL.  
- **Greed periods** also involve high leverage but slightly fewer trades.  
- **Neutral and Extreme Fear phases** show lower risk-taking and fewer trades.  
- Traders adjust behavior (position size and risk exposure) according to market sentiment.  


## Notes
- All code is written in Google Colab notebooks (`.ipynb`).  
- Visual outputs are saved in the `outputs/` folder.  
- The final report summarizing all insights is included as `ds_report.pdf`.  


## Usage
1. Open `notebook_1.ipynb` in Google Colab to run analyses and reproduce plots.  
2. All CSVs are in `csv_files/` and can be loaded directly.  
3. Output images and the final report can be referenced for insights.  


## Colab Link
[Open Notebook in Google Colab](https://colab.research.google.com/drive/15WGCR6P9oTVZq9HkL7GG9VeftoKMbhso?usp=sharing)
```
