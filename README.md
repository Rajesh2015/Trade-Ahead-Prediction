# Stock Market Cluster Analysis Project  

## Objective  
This project focuses on analyzing stock price data and financial indicators for companies listed on the New York Stock Exchange (NYSE). The goal is to group stocks based on their characteristics using clustering techniques and provide actionable insights into the features of each group.  

Trade&Ahead, a financial consultancy firm, aims to use this analysis to deliver personalized investment strategies to its customers.  

---

## Data Description  
The dataset contains information on stock prices and financial indicators such as ROE, earnings per share, and P/E ratio. Below is a summary of the data fields:  

- **Ticker Symbol**: Abbreviation used to uniquely identify publicly traded shares of a particular stock on a stock market.  
- **Company**: Name of the company.  
- **GICS Sector**: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations.  
- **GICS Sub Industry**: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations.  
- **Current Price**: Current stock price in dollars.  
- **Price Change**: Percentage change in the stock price in 13 weeks.  
- **Volatility**: Standard deviation of the stock price over the past 13 weeks.  
- **ROE**: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt).  
- **Cash Ratio**: The ratio of a company's total reserves of cash and cash equivalents to its total current liabilities.  
- **Net Cash Flow**: The difference between a company's cash inflows and outflows (in dollars).  
- **Net Income**: Revenues minus expenses, interest, and taxes (in dollars).  
- **Earnings Per Share**: Company's net profit divided by the number of common shares it has outstanding (in dollars).  
- **Estimated Shares Outstanding**: The number of shares of the company's stock currently held by all its shareholders.  
- **P/E Ratio**: Ratio of the company's current stock price to the earnings per share.  
- **P/B Ratio**: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities).  

---

## Exploratory Data Analysis (EDA) Questions  

1. **What does the distribution of stock prices look like?**  
   Analyze the spread and skewness of stock prices to understand pricing patterns.  

2. **The stocks of which economic sector have seen the maximum price increase on average?**  
   Identify sectors showing significant growth trends based on price changes.  

3. **How are the different variables correlated with each other?**  
   Use correlation analysis to identify relationships between financial indicators (e.g., ROE, P/E Ratio) and stock performance.  

4. **How does the average cash ratio vary across economic sectors?**  
   Examine the ability of companies in each sector to meet short-term obligations using cash equivalents.  

5. **How does the P/E ratio vary, on average, across economic sectors?**  
   Analyze P/E ratios to determine how investors value stocks in different sectors relative to earnings.  

---

## Insights and Recommendations  
The analysis results will be used to identify clusters of stocks with similar characteristics. These clusters will help:  
- Build diversified investment portfolios to reduce risk.  
- Identify undervalued or overvalued stocks for potential investment opportunities.  
- Understand sector-specific financial health and growth potential.  

By leveraging cluster analysis, Trade&Ahead can provide personalized and data-driven investment strategies for its clients.  
