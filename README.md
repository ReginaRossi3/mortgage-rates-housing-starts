# mortgage-rates-housing-starts
Time-series analysis examining whether mortgage rates help explain and forecast U.S. housing starts using R.
# Mortgage Rates and U.S. Housing Starts

This econometrics project examines whether mortgage rates help explain and
forecast quarterly housing starts in the United States.

## Research Question

Do changes in 30-year fixed mortgage rates help predict changes in U.S.
housing starts?

## Data

The analysis uses quarterly U.S. housing-starts and 30-year fixed
mortgage-rate data from 1990 Q1 through 2021 Q2. The data were obtained
from the Federal Reserve Bank of St. Louis.

## Methods

- Time-series exploration and visualization
- Training and holdout samples
- Augmented Dickey-Fuller stationarity tests
- First differencing
- Autoregressive model
- Autoregressive distributed lag model
- Ljung-Box and Breusch-Godfrey diagnostic tests
- Out-of-sample forecasting
- RMSE and MAE model evaluation
- Binary dependent-variable modeling

## Key Findings

Increases in mortgage rates were associated with subsequent decreases in
housing starts. Including mortgage-rate changes improved the model's RMSE,
although the forecasting improvement over the autoregressive model was
relatively modest.

The models performed reasonably well during the early holdout periods but
had difficulty forecasting the unusual housing-market conditions surrounding
the COVID-19 period. This demonstrates an important limitation of models
estimated using historical relationships.

## Tools and Skills

R, time-series econometrics, forecasting, statistical testing, model
diagnostics, data visualization, and out-of-sample evaluation.

## Project Report

[View the complete report](mortgage-rates-housing-starts.pdf)

## Collaboration

This project was completed collaboratively by Regina Rossi, Andre Akopian,
and Nghi Nguyen. My primary contributions included writing the R code,
conducting the econometric analysis, and interpreting the model results.

## Disclaimer

This project was completed for academic and educational purposes.
