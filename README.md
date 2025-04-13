# sp500-vix-analysis
Time series analysis of the S&P 500 and VIX daily price data, 2020–2025 
Learning excel functions and using my economics degree (currently am a senior studying BS econ), this project is to explore the relationship between the VIX and S&P500 using time series regression analysis. 
I found that when regressing  ΔS&P_t = α + β * ΔVIX_t + ε, β=-.41 This relationship has been well documented already. But from my regression, the variance is not stationary, thus, this model suffers from heteroskedasticity. 
