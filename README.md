# Management-Quality-and-Firm-Performance-Econometrics
Empirical analysis of the relationship between management practices and firm size using data from the World Management Survey (WMS).

🚀 Overview

This project studies how management quality (measured by a management score from 1 to 5) is related to firm size (number of employees), focusing on:

- France, 2014 as baseline
- Comparisons with another country & most recent year
- Distributional properties, transformations, correlations, and simple regressions

The work is implemented in Python (Jupyter/Colab) as part of an Econometrics homework.

🛠️ Methods

Part A – Descriptive analysis (France 2014)
- Histograms of management and emp_firm
- Sample mean and standard deviation of management score
- Search for a suitable distribution for both variables
- Transformation of emp_firm (e.g., log) to approximate normality

Part B – Associations
- Firm-size quantiles: small, intermediate, big
- Average management score by size group
- Hypothesis test: big vs small firms’ management scores
- Scatter plots:
  - management vs emp_firm
  - management vs log(emp_firm)
- Correlations and interpretation

Part C – Simple regressions
- OLS: management on emp_firm
- OLS: management on log(emp_firm)
- Compare R² and discuss which specification fits better

Part D – Other country / year
- Repeat Part C for another country in the most recent available year (N ≥ 100)
- Compare results with France 2014
