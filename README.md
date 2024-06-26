# Lack of Robustness of the Markowitz Procedure and the GMV Portfolio
## Project Overview
This project investigates the practical limitations of the Markowitz procedure for portfolio optimization, focusing on its sensitivity to estimation errors in expected returns and covariances. The Markowitz procedure, also known as mean-variance optimization, aims to create an optimal portfolio that maximizes returns for a given level of risk or minimizes risk for a given level of return. However, this method assumes that we have precise estimates of expected returns and covariances, which is rarely the case in practice.
## Key Objectives and Steps
### 1. Sensitivity of Markowitz Procedure to Estimation Errors
Objective: To demonstrate how minor errors in estimating expected returns and covariances can lead to significant changes in the optimal portfolio weights.
#### <br> Steps: <br>
- Loaded historical returns data.
- Calculated the expected returns and covariances for a specified period.
- Created a simple two-asset portfolio and optimized it using the Markowitz procedure.
- Introduced minor errors in the expected returns and observed the resulting changes in portfolio weights.
### 2. Alternative Portfolio Strategies
Objective: To explore portfolio strategies that avoid the sensitivity to estimation errors inherent in the Markowitz procedure.
#### <br> Steps: <br>
- Introduced the Equally-Weighted (EW) portfolio, which assigns equal weight to all assets, avoiding the need for return estimates.
- Introduced the Global Minimum Volatility (GMV) portfolio, which minimizes portfolio volatility by assuming all assets have the same expected return, thus avoiding return estimation.
### 3. Visualization and Comparison
Objective: To compare the traditional Markowitz optimized portfolio with the EW and GMV portfolios visually.
#### <br> Steps: <br>
- Plotted the efficient frontier, showing the set of optimal portfolios.
- Added the EW and GMV portfolios to the plot for comparison.
- Highlighted how the EW portfolio lies inside the efficient frontier but requires no estimation, and how the GMV portfolio provides a low-volatility alternative.
## Conclusion
The project demonstrates that while the Markowitz procedure theoretically offers optimal portfolios, its practical application is fraught with difficulties due to estimation errors. By comparing it with the simpler EW and GMV portfolios, the project highlights the potential benefits of these alternative strategies. The EW portfolio, despite its simplicity, often performs remarkably well, and the GMV portfolio provides a robust, low-risk option without relying on precise return estimates. This exploration underscores the importance of considering robustness and simplicity in portfolio construction, especially in the face of uncertain data.



