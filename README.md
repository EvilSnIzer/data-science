# Trader Behavior vs Market Sentiment — Submission

This project analyzes historical trades joined with the Bitcoin Fear & Greed Index.

## Contents
- `csv_files/`
  - `merged_trades_with_sentiment.csv`
  - `metrics_by_sentiment.csv`
  - `daily_metrics_by_sentiment.csv`
- `outputs/` — charts (PnL timeseries, notional volume, win rates)
- `ds_report.pdf` — summary report with key findings
- `notebook_1.ipynb` — Colab notebook (load CSVs, reproduce pipeline)

## Key Insights
- Win rate higher in **Greed** (40.3%) vs **Fear** (38.8%)
- Aggregate realized **PnL higher in Fear**
- **Extreme Greed** and **Extreme Fear** show distinct patterns
- **Volume** tends to swell in Fear periods

## How to Reproduce
1. Open `notebook_1.ipynb` in Google Colab.
2. Upload `historical_data.csv` and `fear_greed_index.csv`.
3. Run all cells — charts and CSVs will be generated.

## Submission Instructions
- Upload this structure to GitHub with notebook shared via Colab link.
- Email to the specified addresses with subject line:
  **“Junior Data Scientist – Trader Behavior Insights”**
