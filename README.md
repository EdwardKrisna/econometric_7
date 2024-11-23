# Macroeconomic Time Series Analysis

## Overview
This project analyzes macroeconomic time series data from 1959 to 2000 using various regression models to examine relationships between key economic indicators. The analysis focuses on handling serial correlation in time series data using SARIMAX modeling.

## Data Description
The dataset contains quarterly observations of key economic indicators:
- Unemployment Rate (UR)
- Consumer Price Index (CPI)
- Federal Funds Interest Rate (FFIR)
- Treasury Bill Rate (TBILL)
- Annual Bond Rate (TBON)
- Trade-weighted Exchange Rate (ER)
- GDP Growth (GDP)

## Methods
The analysis employs several time series techniques:
1. First differencing for stationarity
2. SARIMAX modeling with:
   - AR(3) for non-seasonal component
   - AR(1) for seasonal component (quarterly)
3. Lagged variable analysis
4. Comprehensive diagnostic testing

## Requirements
```python
pandas
numpy
statsmodels
sklearn
matplotlib
scipy
```

## Key Features
- Handling of serial correlation
- Standardization of variables
- Model comparison and selection
- Comprehensive diagnostics and visualization

## Results
The SARIMAX model successfully addressed serial correlation (Breusch-Godfrey test p-value: 0.314), providing reliable estimates of relationships between economic indicators.
