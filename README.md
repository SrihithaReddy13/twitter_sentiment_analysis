# twitter_sentiment_analysis
B.Tech 7th Semester Project on Twitter Sentiment Analysis for NLP Course.

We analyse tweets from Twitter - both real time (using tweepy) and through a dataset.

Real time Twitter Sentiment Analysis:
  Real time tweets of a user entered keyword are collected using tweepy. The collected tweets are de-emojized using the emoji package.
  To get a general idea of the major keywords, the tweets are visualized in the form of word cloud using wordcloud package.
  Then each tweet is cleaned by removing the stop words, hashtags, users and urls. They are vectorized to form an array of words.
  The sentiment of the tweet is determined using Textblob package and VaderSentiment and display the results.
  Hashtag analysis is then performed by linking the recognized sentiment and the hashtag. Barplots of respective sentiments with the hashtags are visualized.

Twitter Sentiment analysis is also done with a pre-collected tweet dataset. 
  After cleaning the tweets in the DataFrame, MultiNomial Naive Bayes Classification and Logistic Regression are performed. 
  The results along are displayed with confusion matrix and metrics like precision, recall etc.
