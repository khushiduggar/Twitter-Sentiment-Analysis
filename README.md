# Twitter-Sentiment-Analysis
his project is a Python-based sentiment analysis tool that fetches real-time tweets using the Twitter API and classifies them as positive, negative, or neutral based on their content. The classification is done using the TextBlob library, which analyzes the polarity of each tweet.


Features:


Fetches Tweets in Real-Time: Uses Tweepy to interact with the Twitter API, allowing users to search for tweets based on any query.
Sentiment Analysis: Classifies tweets as positive, negative, or neutral by using the TextBlob sentiment analysis model.
Data Cleansing: Cleans tweet text by removing special characters, links, and mentions, ensuring that the sentiment analysis is based on meaningful text.
Customizable Search: Allows users to specify the number of tweets to analyze and the search query.
Output:
The script generates insights such as:

Percentage of positive, negative, and neutral tweets.
Displays a few examples of positive and negative tweets.
Requirements:
tweepy: To interact with the Twitter API.
textblob: For sentiment analysis.
re: For cleaning tweet text using regular expressions.
How to Run:
Clone the repository.
Set up a Twitter developer account and get your API keys.
Update the consumer_key, consumer_secret, access_token, and access_token_secret in the script with your credentials.
