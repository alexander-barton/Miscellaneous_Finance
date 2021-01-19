# PortfolioOptimization

This notebook does various portfolio optimizations for 20 S&P tickers. Data from 2005 - October 2008 are used for estimating parameters.  Performance of the different methods is evaluated on November 2008 data.

Standard MVO, Box and Ellipse MVO, and Risk Parity are implemented.  

Most of the work is done using [CVXPY](https://www.cvxpy.org/).  Scipy optimization is used for Risk Parity.
