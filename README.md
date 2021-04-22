# US-TREASURY YIELDS DATA ANALYSIS

# Dataset:
The trend of 55 years( 1962 to 2017) of US treasury yields insights From the
Fred's website.

# Data Exploration

•The trend of 55 years( 1962 to 2017) of US treasury yields insights From the
Fred's website it is clear that

•As we can see the yields around 1980 for all maturity lengths was significantly
high approx 16 compared to those of present( approx 2-3%)

•We can see great recession between 2007 and 2009

•Most of the public holiday and weekend data is missing

•Some short terms yields are missing during most of the years
US Treasury

# Data Preprocessing

•Missing weekend and public holiday data because markets close.

•Considering 1 year, 3 year, 5 year and 10 year yields.

•Yield rates are most correlated with the values from their immediate past e.g.
yield on Monday = yield on Friday.

•For weekends and public holiday instead of imputing values, we modified the
time series such that there are no breaks after we ignore the weekend &
public holiday timestamps.

# Conclusion:

•During this project got an idea about US treasury yields for multiple tenors.

•In python we are mainly using six libraries- pandas, numpy, seaborn, matplotlib.pyplot, scipy, statsmodels.

•Logistic Distribution fits better than Normal Distribution for all the increments

•Determined the Term Structure of Yield

•Identified that there are correlations between 1 day and 25 day increment for multiple tenors by Pearson's method.

•SARIMA Stochastic Model is implemented to predict Yields.

•Future Scope: To implement Stochastic model like Geometric Brownian motion for predicting yields.
