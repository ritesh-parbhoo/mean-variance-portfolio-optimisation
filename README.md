MEAN-VARIANCE PORTFOLIO OPTIMISATION

DESCRIPTION

This project, implemented in R, explores portfolio optimisation and risk analysis using historical asset prices. It begins by collecting historical daily price data, computing daily returns, and annualising them to derive the mean returns vector and covariance of returns matrix. Using these inputs, an efficient frontier is plotted to determine efficient portfolio weight combinations. A Monte Carlo simulation is employed to generate potential asset returns scenarios, assuming asset returns follow a multivariate normal distribution, leading to the calculation of risk measures such as Value at Risk (VaR) and Expected Shortfall (ES). Efficient portfolios are then compared across these risk measures, offering an integrated assessment of efficiency and risk-adjusted performance. Statistical analysis, optimisation techniques, and simulation-based risk evaluation are implemented to demonstrate practical applications of mean-variance portfolio theory.

REFERENCE LIST

Data:
Source: Yahoo!Finance
URLs:
finance.yahoo.com/quote/AAPL
finance.yahoo.com/quote/XOM
finance.yahoo.com/quote/GLD
finance.yahoo.com/quote/TLT
finance.yahoo.com/quote/WMT

Packages:
quantmod
Ryan JA, Ulrich JM (2025). _quantmod: Quantitative Financial Modelling Framework_. doi:10.32614/CRAN.package.quantmodhttps://doi.org/10.32614/CRAN.package.quantmod, R package version 0.4.28, https://CRAN.R-project.org/package=quantmod.
PerformanceAnalytics
Peterson BG, Carl P (2024). _PerformanceAnalytics: Econometric Tools for Performance and Risk Analysis_. doi:10.32614/CRAN.package.PerformanceAnalytics https://doi.org/10.32614/CRAN.package.PerformanceAnalytics, R package version 2.0.8, https://CRAN.R-project.org/package=PerformanceAnalytics.
quadprog
dpodi/LINPACK) SobBATRpbAW<FcfCM (2019). _quadprog: Functions to Solve Quadratic Programming Problems_.doi:10.32614/CRAN.package.quadprog https://doi.org/10.32614/CRAN.package.quadprog, R package version 1.5-8, https://CRAN.R-project.org/package=quadprog.
MASS
Venables, W. N. & Ripley, B. D. (2002) Modern Applied Statistics with S. Fourth Edition. Springer, New York. ISBN 0-387-95457-0
ggplot2
H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016.
knitr
Xie Y (2025). _knitr: A General-Purpose Package for Dynamic Report Generation in R_. R package version 1.51, https://yihui.org/knitr/.
Yihui Xie (2015) Dynamic Documents with R and knitr. 2nd edition. Chapman and Hall/CRC. ISBN 978-1498716963
Yihui Xie (2014) knitr: A Comprehensive Tool for Reproducible Research in R. In Victoria Stodden, Friedrich Leisch and Roger D. Peng, editors, Implementing Reproducible Computational Research. Chapman and Hall/CRC. ISBN 978-1466561595


REPRODUCIBILITY

R version 4.5.2 (2025-10-31 ucrt)
