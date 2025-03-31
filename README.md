# Economic Indicator Analysis & Forex Trends

![screenshot-localhost_8888-2025 03 31-15_22_34](https://github.com/user-attachments/assets/218c3c57-b895-4036-beee-a57339262d07)

### Project Overview

This project explores the relationship between economic indicators—GDP, inflation, and interest rates—and their impact on foreign exchange (Forex) rates. Using historical data from 2000 to 2019, we analyze trends, correlations, and macroeconomic influences on currency valuation, specifically focusing on the USD exchange rate.

### Project Goals
- Understand how GDP growth, inflation, and interest rates influence forex trends.
- Identify correlations between economic indicators and exchange rates.
- Visualize trends and statistical relationships.

### Data Sources

- Forex Data: Daily exchange rates from 2000 to 2019 for major currencies.
- Economic Indicators: GDP, inflation, and interest rates obtained through simulation (due to API limitations).

### Implementation Steps

1. Data Collection & Preprocessing
- Convert daily forex data to monthly averages.
- Validate the presence of USD data.
- Simulate economic indicators if real API data is unavailable.

2. Data Analysis & Visualization
- Normalize and plot economic indicators vs. exchange rates.
- Compute correlation matrices to assess relationships.
- Generate heatmaps and time-series visualizations.

3. Statistical Insights
- Compute mean, standard deviation, min/max values for each variable.
- Identify key patterns, such as the impact of inflation and GDP on currency strength.

### Results & Interpretation

- Analyze negative correlations between GDP/inflation and the exchange rate.
- Assess the unexpected negative correlation between interest rates and the USD.
- Draw conclusions on macroeconomic interactions and potential forex trends.

### Key Findings

- Higher GDP and inflation were linked to a weaker USD (negative correlation: -0.53, -0.54).
- Interest rates also showed a negative correlation (-0.55), suggesting complex dynamics in forex valuation.
- GDP, inflation, and interest rates were strongly correlated (~0.92-0.95), indicating intertwined economic factors.

### Future Improvements

1. Incorporate real-world economic data APIs (World Bank, ECB, FRED).
2. Use machine learning models to predict forex trends based on macroeconomic factors.
3. Explore geopolitical influences on currency movements.


### Source

![Forex Exchange Rates Since 2004 from Kaggle](https://www.kaggle.com/datasets/asaniczka/forex-exchange-rate-since-2004-updated-daily)
