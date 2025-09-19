# Sentiment Factor with FinBERT

This project builds a sentiment-based alpha factor using financial news headlines, fine-tunes FinBERT (ProsusAI/finbert) in TensorFlow, and backtests the factor against SPY.

## Project Structure
- Notebook: End-to-end workflow (training → factor → backtest)
- requirements.txt: dependencies
- results.png: cumulative returns plot

## Phases
1. Setup & Data Collection
2. Sentiment Model (FinBERT fine-tuning)
3. Factor Construction
4. Backtest & Evaluation
5. Documentation & GitHub

## Extensions
- Add transaction costs
- Compare against momentum factor
- Ensemble with other NLP models
