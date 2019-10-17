# Hello Twitter, how are you feeling today?
Scraping tweets off of twitter with a specified hashtag and analysing its sentiment.

## What are we trying to do?
- Given a set of tweets in text format, can we try and figure out a way to understand the tone of the person who wrote it? 
- Can we identify if it's a positive, negative or neutral emotion that is being conveyed?

## What steps did we follow?
- Created Twitter credentials to use the Twitter APIs
- Fetched a set number of tweets off Twitter, based on the user input hashtag
- Cleaned the tweets (removing urls, user mentions etc.)
- Using python's textblob library, analysed each tweet and classified as positive, negative or neutral

## Additional notes:
References are as follows:
- https://textblob.readthedocs.io/en/dev/advanced_usage.html#sentiment-analyzers
- https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/
- https://www.promptcloud.com/blog/scrape-twitter-data-using-python-r/


