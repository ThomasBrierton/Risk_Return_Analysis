# Risk_Return_Analysis

This is a risk-return analysis of four large investment portfolios compared to the S&P 500. The prupose of this analysis is to determine which fund has investment potential, taking the following key factors into consideration: daily returns, standfard deviation, variance/covariance, Sharpe Ratios, and their beta in relation to the S&P 500. Soros Fund Management LLC, Paulson & Co Inc, Tiger Global Management, and Berkshire Hathaway are the four funds taken into consideration for this analysis.

---

## Technologies 

This project uses Jupyter Notebook (within JupyterLab) and the standard Python 3.8 libraries. In addition, this project requires the following libraries and/or dependencies:

Pandas - a software library designed for open source data analysis and manipulation

Pathlib - a Python module which provides an object API for working with files and directories

Numpy - a Python library for mathematical functions

matplotlib - a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy

---

## Methods

In order to complete this risk-return analysis, the follwing steps were completed:

Step 1: Collect the data and analyze the performance of the four fund portfolios and the S&P 500.

Step 2: Analyze the volatility and plot the results

Step 3: Analyze the risk - Calculate the standard deviation, including the anualized and 21-day rolling standard deviations.

Step 4: Calculate the risk-return profile using the Sharpe Ratio. 

Step 5: Calculate the betas of each fund compared to the S&P 500.

Step 6: Determine which fund to allocate investments.

*To follow along and see more in-depth comments, please review the risk_return_analysis.ipynb Jupyter Notebook file.

---

## Analysis

After conducting the risk-reuturn analysis, the S&P 500 appears to outperform all four of the analyzed fund portfolios. Aside from the S&P 500, Berkshire Hathaway is the highest performing portolio with the best risk-reward profile.

![](https://github.com/ThomasBrierton/Risk_Return_Analysis/blob/main/Photos/Cumulative_Returns_Whale_Funds.png)

![](https://github.com/ThomasBrierton/Risk_Return_Analysis/blob/main/Photos/Whale_Returns_Volatility.png)

![](https://github.com/ThomasBrierton/Risk_Return_Analysis/blob/main/Photos/21-Day_Rolling_STD_Whale.png)
---

## Contributors

Thomas Brierton and UCB

---

## License

MIT