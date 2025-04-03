# VaR Analysis: Historical, Bootstrap & Monte Carlo 
This repo estimates Value at Risk (VaR) using historical simulation, bootstrapping, and Monte Carlo methods, providing insights into portfolio risk assessment.
 
### Overview  
This project analyzes financial risk using **Value at Risk (VaR) for a 4-stock portfolio (AAPL, AMZN, GOOGL, MSFT). We estimate 99% VaR using:  
- Historical Simulation – Based on past returns.  
- Bootstrapping – Resampling historical data for robust estimation.  
- Monte Carlo Simulation (t-distribution) – Accounts for fat tails and extreme market conditions.  

### Key Findings  
- Historical VaR: $4,235 – Simple but limited by past data.  
- Bootstrap VaR: $4,249 (Range: $3,909 - $4,892) – More robust estimation.  
- Monte Carlo VaR (t-distribution): $3,986 – Captures extreme fluctuations.  

### Conclusion  
Each method offers unique risk insights. Monte Carlo (t-distribution) provides a more realistic estimate for volatile markets, avoiding the limitations of assuming normality.  

