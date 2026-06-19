# Time-Varying Beta Estimation

## Overview
Comparison of three econometric approaches for estimating 
time-varying beta coefficients in financial markets.

## Methods
- Rolling OLS
- Kalman Filter  
- DCC-GARCH

## Data
Daily stock returns [August 2001 - May 2026], [ DAX 40: Munich Re, BASF, BMW, Deutsche Bank, Deutsche Telekom, In
fineon, SAP, Siemens \  S&P 500: Apple, Goldman Sachs, Johnson & Johnson, JPMor
gan Chase, 3M, Nvidia, Procter & Gamble,  ExxonMobil]
Risk-free rate for the EU sample is the German Bubill 1-Month yield, retrieved
as an annualised yield to maturity and converted to a daily rate by dividing by 252
Risk-free rate for the US sample is the
US Treasury Bill 1-Month yield, likewise converted to a daily equivalent by dividing
by 252

## Results


## Technologies
Python | pandas | statsmodels | arch | pykalman