# Web-Scraping-Project-1-

NYC Data Academy Project 1 - WallStreetBets Analysis

WSB DATA SUBDIRECTORY will contain daily data taken from WSB subreddit:
(Description of the rows below:)

•	ticker: The stock ticker.
•	date: The day that the current data is from.
•	url: The url of the stock on Yahoo Finance.
•	num_mentions: The number of times the stock ticker was seen in any posts or comments for this day.
•	pct_mentions: The number of mentions of this stock as a percentage of all stock ticker mentions for this day.
•	pos_count: The number of times this stock was mentioned within a (predicted) positive context for this day.
•	neg_count: The number of times this stock was mentioned within a (predicted) negative context for this day.
•	bullish_pct: The number of positive sentiment mentions as a percentage of all the mentions of this stock for this day.
•	bearish_pct: The number of negative sentiment mentions as a percentage of all the mentions of this stock for this day.
•	neutral_pct: The number of mentions that were not classified as either positive or negative as a percentage of all the mentions of this stock for this day.
•	price: The price of this stock as of market close (usually) from the previous day. This data was scraped daily from Yahoo Finance. See the time_of_price column to confirm what time the price was actually reported from the previous day (some say like 11AM for some reason).
•	price_change_net: The change in price of the stock as a dollar amount from the previous market open to the previous market close.
•	price_change_pct: The change in price of the stock as a percentage from the previous market open to the previous market close.
•	time_of_price: The time at which this price was reported on Yahoo Finance.

Merged all these files and cleaned as 'WSB.csv'  This was the main data file used for the WallStreetBets' portion. (obtained these from Alex)

