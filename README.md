# Stock Market Dynamics During Economic Crises: A Sectoral Study (1999-2019)

## Overview
This project analyzes the impact of economic crises, including the 2008 Financial Crisis and the Dot-Com Bubble, on stock market dynamics. Using a hybrid approach of econometric models and machine learning techniques, the study focuses on sector-specific behaviors across 481 companies in the S&P 500 index.

Key findings include:
- Financials and Technology sectors exhibit the highest sensitivity to crises.
- Utilities and Consumer Staples demonstrate resilience with lower volatility.
- Machine learning models outperformed traditional econometric methods in forecasting.

## Research Objectives
1. Analyze sectoral volatility and trading volume during economic crises.
2. Identify sectors that are resilient or sensitive to economic shocks.
3. Utilize stable-period data to forecast sectoral behavior during crises.

## Methodology
The project employs the following methods:
1. **Event Study Analysis**: Examines abnormal returns and trading volumes during crisis periods.
2. **ARIMA Models**: Captures price trends in stable periods.
3. **LSTM Models**: Forecasts trends during volatile periods.
4. **Machine Learning Models**:
   - Random Forest
   - XGBoost
5. **Volatility and Performance Analysis**: Highlights sector-specific trends.
6. **Trading Volume and RSI Analysis**: Tracks investor behavior and market sentiment.

## Dataset
- **Source**: S&P 500 Index data (1999-2019)
- **Features**:
  - Open, High, Low, Close prices
  - Sectoral segmentation: Technology, Healthcare, Finance, Consumer Goods, and more
  - Volatility and trading volume metrics

## Results
- **Sensitivity of Sectors**:
  - Financials and Technology: High volatility, slow recovery.
  - Utilities and Consumer Staples: Low volatility, fast recovery.
- **Predictive Models**:
  - Machine Learning: 85% accuracy in sectoral forecasts.
  - ARIMA: 72% accuracy, less effective during crises.
- **Portfolio Insights**:
  - Defensive sectors provide stability during downturns.
  - Diversification reduces risk in volatile periods.

## Key Contributions
1. Combines econometrics and machine learning for granular sector analysis.
2. Focuses on sector-specific patterns rather than aggregated market indices.
3. Provides actionable insights for investors and policymakers.

## Directory Structure
