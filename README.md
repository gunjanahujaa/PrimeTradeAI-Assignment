#  PrimeTrade.ai Hiring Assignment

## Overview

This repository contains my submission for the **PrimeTrade.ai Data Analytics Hiring Assignment**.

The objective of this project is to analyze cryptocurrency trading behavior by combining historical trade data with the **Fear & Greed Index** to identify how market sentiment influences trading activity, profitability, and trading patterns.

---

##  Project Structure

```
PrimeTradeAI-Assignment/
│
├── internship_assignment_by_Gunjan_Ahuja.ipynb    # Complete analysis notebook
├── requirements.txt                              # Required Python libraries
├── README.md                                     # Project documentation
│
└── data/
    ├── historical_data.csv
    └── fear_greed_index.csv
```

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Loading
- Loaded Historical Trades dataset
- Loaded Fear & Greed Index dataset

### 2. Data Understanding
- Dataset inspection
- Data types analysis
- Missing value analysis
- Duplicate row analysis
- Date range exploration

### 3. Data Cleaning
- Converted date columns to datetime format
- Verified data consistency

### 4. Feature Engineering
Created additional features including:
- Date
- Year
- Month
- Day of Week
- Hour
- Sentiment Score

### 5. Exploratory Data Analysis (EDA)

#### Historical Trades Analysis
- Trades by Coin
- Buy vs Sell Distribution
- Closed PnL Distribution
- Trading Activity by Day of Week

#### Fear & Greed Index Analysis
- Sentiment Distribution
- Index Value Distribution
- Sentiment Trend Over Time
- Average Index Value by Sentiment

#### Merged Dataset Analysis
- Average Profit by Market Sentiment
- Number of Trades by Market Sentiment
- Average Trade Size by Market Sentiment
- Buy vs Sell Analysis across Market Sentiments
- Correlation Heatmap

---

##  Key Insights

- Fear was the most frequently observed market sentiment.
- Buy and Sell trades were nearly balanced across the dataset.
- Trading activity was highest during weekdays and comparatively lower on weekends.
- Average trade profitability varied across different market sentiments.
- Trade size also differed between sentiment categories.
- Strong positive correlation was observed between **Fee** and **Trade Size (USD)**.
- Market sentiment alone showed only a weak direct linear correlation with trade profitability.

---

##  How to Run

1. Clone the repository

```bash
git clone https://github.com/gunjanahujaa/PrimeTradeAI-Assignment.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
internship_assignment_by_Gunjan_Ahuja.ipynb
```

4. Run all cells sequentially.

---

##  Repository Contents

- Complete exploratory data analysis
- Feature engineering
- Data visualization
- Merged sentiment analysis
- Statistical summaries
- Correlation analysis

---

## 👩‍💻 Author

**Gunjan Ahuja**

GitHub: https://github.com/gunjanahujaa
