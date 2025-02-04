# Stock Market Performance Analysis 

## Overview
This project conducts an EDA of historical stock price data from multiple companies to uncover key trends, volatility, and performance over time. Using Excel, the analysis provides an interactive dashboard for dynamic exploration of stock data, enabling users to filter by specific stock tickers, time periods, and price movements.

## Objective
To analyze historical stock price data to gain insights into stock performance, trends, and volatility.By using Excel’s built-in tools (such as slicers, timelines, and charts), the project aims to assist investors and decision-makers in making data-driven investment choices by identifying stock trends, understanding market behavior, and assessing risk.

### Key Areas of Focus:
- Stock price trends over time using moving averages and time-series analysis
- Volatility analysis to assess stock price fluctuations
- Correlation analysis to understand relationships between different stocks
- Descriptive statistics to summarize key performance metrics
- Dashboard to visualize stock performance and key insights

## Data Sources
- Yahoo Finance (yfinance): Used to fetch historical data for select group of stocks, Python code [File](https://github.com/gautamnakum40/Stock_Market_Performance_Analysis_Using_Advanced_Excel/blob/main/import-stocks-data.ipynb)
-  It includes stock prices, trading volumes, and related metrics.
-  Data from 2019-2024 was collected for long-term analysis of  market trends for last 5 years.

## Tools and Technologies I Used
- Using python(Jupyter Notebook) fetch historical data from yfinance (Yahoo Finance API)
- Microsoft Excel for data analysis and visualization
- Pivot Tables and Charts for data summarization and reporting
- Descriptive statistics, moving averages, and correlation matrices for analysis
- Conditional formatting and slicers for dynamic reporting
- Time series and volatility analysis techniques
-  Git and GitHub for version control.

## Skills Demonstrated
- Exploratory Data Analysis (EDA) of financial datasets.
- Time series and volatility analysis.
- Data visualization using Excel dashboards.
- Statistical analysis of stock performance.
- Data-driven decision making in finance.
- Use of Excel features and tools like pivot tables, pivot charts, conditional formatting, slicers, timeline, different types of charts. 
- Key functions like xlookup(), iferror(), index-match(), multiple if functions like a countif(), averageif(), statistical functions stddev(), median(), percentile.inc() etc.. 

## Project Structure
### 1. **Time Series Analysis**
   
#### Question:  _What insights and trend of stock prices for RELIANCE.NS, TCS.NS, HDFCBANK.NS,INFY.NS, and HINDUNILVR.NS over the given period?_

#### Visualization:
![stock_performance_image](https://github.com/gautamnakum40/Stock-Market-Performance-Analysis-using-Excel/blob/main/stock_analysis_img/stocks%20performance.png)

#### Insights:
* Growth Potential: The upward trend across all stocks suggests positive growth potential in the Indian stock market for these companies.
* Investment Considerations: Investors might consider TCS.NS and RELIANCE.NS for potentially higher returns, albeit with higher risk due to volatility.
* Market Stability: HINDUNILVR.NS and HDFCBANK.NS may offer more stable investment options with less price fluctuation.

### 2. **Volatility Analysis**
   
#### Question:_What trends can be observed in the volatility of these stocks over the years 2019 to 2024?_

#### Visualization:
![volatility_image](https://github.com/gautamnakum40/Stock-Market-Performance-Analysis-using-Excel/blob/main/stock_analysis_img/stddiv.png)
#### Insights:
* Peak Volatility in 2020: Most stocks experienced their highest volatility in 2020, likely due to market disruptions.
* General Decline Post-2020: A general trend of decreasing volatility is observed from 2021 to 2023 across most stocks.
* Volatility Patterns: RELIANCE.NS and TCS.NS exhibit the highest volatility in 2020, while HINDUNILVR.NS shows a gradual increase in volatility towards 2024.

### 3. **Daily Return Analysis**
   
#### Question:_Which stocks have consistently outperformed or underperformed?_
#### Visualization:
![daily_return_image](https://github.com/gautamnakum40/Stock-Market-Performance-Analysis-using-Excel/blob/main/stock_analysis_img/daily%20return%20movement.png)
#### Insights:
* HDFCBANK.NS and TCS.NS consistently showed positive returns throughout the analyzed period, indicating strong performance.
* RELIANCE.NS experienced significant volatility, with both substantial gains and losses.
* INFY.NS and HINDUNILVR.NS had more moderate returns, with some periods of growth and others of decline.

### 4. **Descriptive Statistics**
   
#### Question: _How can statistics help the stock market?_
#### Visualization:
![statistics_image](https://github.com/gautamnakum40/Stock-Market-Performance-Analysis-using-Excel/blob/main/stock_analysis_img/de_statistics.png)
#### Insights:
- Summary Statistics:

    - Mean: The average closing price for each stock over the analyzed period.
    - StdDev: The standard deviation, measuring the volatility or dispersion of 
prices.
    - Max: The highest closing price.
    - Min: The lowest closing price.
    - Sparklines: Visual representations of price movements.

* TCS.NS has the highest mean and maximum price, indicating strong overall performance.
* HDFCBANK.NS has the lowest standard deviation, suggesting relatively stable price movements.
* RELIANCE.NS has the highest standard deviation, indicating significant price volatility.
* INFY.NS has the lowest minimum price, suggesting potential for significant downside risk.

### 5. **Correlation Matrix**
   
#### Question:_What are the overall correlations between the stocks?_
#### Visualization:
![heatmap_image](https://github.com/gautamnakum40/Stock-Market-Performance-Analysis-using-Excel/blob/main/stock_analysis_img/heatmap.png)
#### Insights:
* Strong Positive Correlation:
   - RELIANCE.NS and TCS.NS: These stocks exhibit a strong positive correlation 
     (0.92), suggesting they tend to move together.
   - HDFCBANK.NS and TCS.NS: A moderately strong positive correlation (0.83)            exists between these stocks.
* Weak Correlations:
   - HINDUNILVR.NS and other stocks: HINDUNILVR.NS shows relatively weak               correlations with the other stocks, indicating a less synchronized movement.

## Final Stock Performance Dashboard
#### Visualization:
![Dashboard image](https://github.com/gautamnakum40/Stock_Market_Performance_Analysis_Using_Advanced_Excel/blob/main/stock_analysis_img/Dashboard.png)

## Summary and Recommendations
Based on the analysis, the following recommendations are made:
##### **Moving Average Strategy**: 
Investors can use the 50-day moving average as a guide for buy/sell decisions, buying when the stock price crosses above the MA 50 and selling when it falls below.

##### **Volatility Monitoring**: 
Keep an eye on periods of high volatility, as they present both risks and opportunities. Risk-averse investors may prefer to avoid highly volatile stocks, while more aggressive investors might capitalize on these movements.

##### **Diversification**: 
Leverage the insights from the correlation matrix to diversify portfolios. Avoid stocks with high positive correlations to reduce risk and ensure better portfolio performance during market downturns.

## Conclusion
This project offers valuable insights into stock performance, volatility, and relationships between stocks. The analysis can support data-driven decision-making in the stock market, helping investors optimize their portfolios and manage risk effectively.

