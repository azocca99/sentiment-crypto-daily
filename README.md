# Sentiment and Cryptocurrency Daily Data

This repository accompanies the MSc thesis *"Investor Sentiment, Bitcoin, and Asset-Specific Dynamics in Cryptocurrency Markets"* (Erasmus University Rotterdam, 2025).

The study investigates the role of investor sentiment in predicting daily cryptocurrency returns, focusing on both individual coins and functional groups (e.g., utility, asset, payment tokens). Using daily data for 124 cryptocurrencies (2015–2025), predictive regressions were estimated with multiple sentiment proxies (VIX, Fear & Greed Index, Twitter-based indices, investor surveys, and policy uncertainty), together with macroeconomic and on-chain controls. The findings suggest that sentiment influences cryptocurrency returns in asset-specific and time-dependent ways, but does not provide systematic predictive power across the market or functional groups.

---

## Repository Structure

- **Data/**
  - **Raw Data/** – Original data downloaded from CoinMetrics, FRED, and other sources (placeholder due to vendor restrictions).
  - **Cleaned Datasets/** – Pre-processed datasets ready for analysis.
  - `cryptomap.csv` – Classification of cryptocurrencies into functional groups.
  - `date_range_per_symbol.csv` – Coverage periods for each asset.
  - `new_cleaned_crypto_data.csv` – Final merged dataset used in regressions.

- **Figures/** – Visual outputs (plots, violin plots, correlation matrices, regression figures).

- **Regressions/**
  - Scripts and outputs from predictive regressions.
  - `Regressions.ipynb` – Main notebook running regression models.

- **Summary Statistics/**
  - Descriptive analysis and tables summarizing variables and proxies.
  - `Summary.ipynb` – Notebook computing summary statistics.

- **Jupyter Notebooks**
  - `Data_Extraction.ipynb` – Downloading and formatting raw data.
  - `Data_Cleaning.ipynb` – Processing, merging, and transforming datasets.
  - `Regressions.ipynb` – Running predictive regressions.
  - `Summary.ipynb` – Generating descriptive statistics.

---

> Zoccarato, A. (2025). *Investor Sentiment, Bitcoin, and Asset-Specific Dynamics in Cryptocurrency Markets*. MSc Thesis, Erasmus University Rotterdam.
