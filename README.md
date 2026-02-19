# Sentiment-Driven Trading Model

## Objective
Build a predictive model using trader behavioral and market sentiment features to predict next-day trader profitability.

## Dataset
- Historical trading data
- Fear & Greed sentiment index

## Methodology
1. Data cleaning and preprocessing
2. Merging trading data with sentiment index
3. Feature engineering:
   - trade_count
   - avg_trade_size
   - long_short_ratio
   - abs_pnl
   - sentiment classification
4. Target creation:
   - Next-day profitability label
5. Logistic Regression model
6. Evaluation using Accuracy, Precision, Recall, F1-score

## Results
- Accuracy: ~56–57%
- Balanced class performance after class weighting
- Sentiment alone is not strongly predictive

## Key Insights
- Extreme sentiment does not guarantee next-day profitability
- Behavioral metrics improve predictive power
- Model performance suggests weak but non-random signal

## How to Run
1. Install required libraries:
   pip install pandas numpy scikit-learn matplotlib seaborn
2. Open notebook
3. Run all cells in order

## Future Improvements
- Add rolling features
- Use time-series cross validation
- Try tree-based models (XGBoost / Random Forest)
- Build a Streamlit dashboard
