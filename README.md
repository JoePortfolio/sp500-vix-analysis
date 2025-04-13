# sp500-vix-analysis
I calculated the Pearson correlation coefficient between the daily changes in the S&P 500 and VIX over the 2020–2025 period and found a correlation of approximately **−0.41**.  
This confirms the well-documented inverse relationship between equity markets and volatility expectations.

How do changes in the VIX affect daily movements in the S&P?
I ran an OLS regression of the S&P on changes in the VIX between 2020 and 2025. 
Model: ΔS&P = α + β * ΔVIX + ε

R²=0.1743	
β =−0.498
Standard Error=0.0306	
t-stat=−16.28	
p-value=3.38 × 10⁻⁵⁴	
95% CI for β	[−0.558, −0.438]	

This regression confirms a statistically and economically significant inverse relationship between daily changes in the VIX and the S&P 500, with a β coefficient of −0.498 and a p-value near zero. While the model explains ~17% of the variation in daily S&P movements, it suffers from heteroskedasticity. 
