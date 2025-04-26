# STOCK DATA ANALYSIS REPORT

# Overview:

Total Rows: 93,612

Total Columns: 7

Stock Symbols (Companies): 31 unique (e.g., AAPL, MSFT, MMM, etc.)

Date Range: Data is likely over several years

No missing values.

# COLUMN DESCRPTION

1.	Highest: Closing Price: 1,195 
2.	Date : Date of the stock data
3.	Open:	Opening price of the stock that day
4.	High:	Highest price of the day
5.	Low:	Lowest price of the day
6.	Close:	Closing price
7.	Volume: Number of shares traded
8.	Name:	Stock ticker (company name)


 # Key Stats: 
Average Closing Price: 85.64
Highest Trading Volume: Over 843 million shares
Most Traded Company (by record count): "MMM" with 3020 entries

# Data Cleaning Steps
This were the steps taken to transform this dataset for analysis:
1.	Removed any rows with null or missing values.
2.	Verified there were no duplicate entries.
3.	Converted volume to a whole number.
4.	Converted the date column to a proper date format.
5.	Rounded prices to 2 decimal places for better results
6.	All prices columns were in decimal format.
   
# Sample Analytical Questions

**Questions asked using SQL:**
	What is the average closing price?
	Which stock had the highest trading volume overall
	What is the yearly average close price of each stock?
	What was the closing price over the years for a selected stock?

# Conclusion
This dataset provides valuable insights into the stock price trends over time. with the right transformation,  it can support trend analysis using power bi and SQL
