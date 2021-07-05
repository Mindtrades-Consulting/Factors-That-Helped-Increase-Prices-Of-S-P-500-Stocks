# Factors-That-Helped-Increase-Prices-Of-S-P-500-Stocks
For successful buying and selling transactions, you should know which factors affect the stocks, interpret them and read the price charts, which we do in this article. 
We divide the factors affecting the stocks traded in the market into two groups. The first group is micro factors and covers the performance of companies and sectors in general. The second group is macro factors and refers to events that occur around the world. Factors such as the growth of companies, profitability, and indebtedness, market cap size are some of the components that affect the stock prices. In addition, sectoral developments may also affect costs.

# Data Sources
We will use beautiful soup in order to get the tickers from Wikipedia. In addition, we will use web.DataReader method in order to get the data from Yahoo Finance from 2010 to 2019. Then, we will check if there are missing values in our data. After cleaning and processing the data we will use matplotlib for visualization. 
List of S&P 500 Companies: https://en.wikipedia.org/wiki/List_of_S%26P_500_companies

# Data Analysis
The data used in this article was gathered from Yahoo Finance using web.DataReader method. Amazon, Google, AMD, Microsoft and S&P 500 stocks are used as examples in this article. The dataset used in the article includes data between 2010 and 2019. 
After scraping the data we will use to_csv method and save the data as sp500_df.csv. Using the sp500_df.head() method, we will see the first five rows in our data. It is easy to see there are multiple variables in the dataset such as data, open, close, high, low, volume and adj close.

#  About the Factors That Affect the Increase in Stock Prices
We’ve saved the key factors into a csv file named as campany-financials.csv. Before beginning the analysis, it would be beneficial to define what the factors mean:
•	Price: Price per share of the company
•	Price to Earnings (PE): The ratio of a company’s share price to its earnings per share
•	Dividend Yield: The ratio of the annual dividends per share divided by the price per share
•	Earnings Per Share (EPS): A company’s profit divided by the number of shares of its stock
•	52 week high and low: The annual high and low of a company’s share price
•	Market Cap: The market value of a company’s shares (calculated as share price x number of shares)
•	EBITDA: A company’s earnings before interest, taxes, depreciation, and amortization; often used as a proxy for its profitability
•	Price to Sales (PS): A company’s market cap divided by its total sales or revenue over the past year
•	Price to Book (PB): A company’s price per share divided by its book value

# Summary  
This article examined how stocks performed between 2010 and 2019 and what factors affected the stock price increase. It is obvious to see that Amazon achieved better growth than other companies. 
In addition, we have seen that factors such as earnings per share, market cap, 52 weeks low, and 52 week high are effective in increasing stock prices. 
After analyzing the visuals, it is safe to say that these factors can potentially drive stock prices.

# How Can You Benefit from These Factors?
If you are trading, you may need to do some research on stocks before you start trading. By examining these factors, for example, by looking at the market cap size, you can decide whether the stock has growth potential. 
You can examine the purchase and sales strategy again and make choices accordingly. You can also predict which stocks might see growth in the future and invest, therefore. 

# How can MindTrades help?
MindTrades Consulting Services, a leading marketing agency provides in-depth analysis and insights for the global IT sector including leading data integration brands such as Diyotta. From Cloud Migration, Big Data, Digital Transformation, Agile Deliver, Cyber Security, to Analytics- Mind trades provides published breakthrough ideas and prompt content delivery. For more information, check mindtrades.com.


