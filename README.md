# trading-sentiment-analysis
Analysis of trader behavior vs market sentiment using Fear &amp; Greed Index. Includes segmentation, strategies, and prediction model.

# Trading Behavior vs Market Sentiment Analysis

This project analyzes trader behavior based on market sentiment (Fear vs Greed) using trading history and sentiment data.

## Dataset
- historical_data.csv → Trading history
- fear_greed_index.csv → Market sentiment

## Objectives
- Compare trader performance during Fear vs Greed
- Analyze behavior changes
- Identify trader segments
- Propose strategies
- Build predictive model

---

## Setup

Install dependencies:

```bash
pip install pandas matplotlib scikit-learn
```

---

## How to Run

Run the script:

```bash
trading_sentiment_analysis.py
```

OR open the notebook:

```
trading_sentiment_analysis.ipynb
```

---

## Files

| File | Description |
|------|-------------|
analysis.py | Main analysis script
analysis.ipynb | Notebook version
writeup.md | Summary report
outputs/ | Charts
data/ | Dataset

---

## Analysis Included

✔ PnL vs Sentiment  
✔ Win Rate  
✔ Trade Behavior  
✔ Trader Segments  
✔ Strategies  
✔ Prediction Model  

---

## Example Insights

- Traders perform worse during Fear
- More trades happen during Greed
- Large positions increase losses

---

## Strategies

1. Reduce leverage during Fear
2. Increase trading during Greed
3. Limit position size during volatility

---
