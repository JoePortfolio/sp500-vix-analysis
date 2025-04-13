# sp500-vix-analysis
This project explores the relationship between the S&P 500 and the VIX using time series regression analysis. As a senior pursuing a B.S. in Economics, I used this project to apply econometric concepts while improving my technical proficiency in Excel.
The core regression model is:
ΔS&Pₜ = α + β * ΔVIXₜ + ε
I found β ≈ −0.41, which confirms the well-documented inverse relationship between changes in market volatility (VIX) and equity prices (S&P 500).
Preliminary stationarity checks suggest that the mean of the differenced closing prices (ΔS&P and ΔVIX) appears stationary, though not formally tested. However, variance is clearly not constant over time, indicating the presence of heteroskedasticity, a known feature of financial time series. This limitation is noted in the interpretation of the model.
