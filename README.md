# Project-Fletcher

I utilized unsupervised machine learning to analyze daily tweets directed towards major news sources.  

The first step of the process involved using Tweepy to stream about 20,000 tweets containing the key words CNN, Fox News, Economist, and Wall street Journal.  These steps are detailed in the Twitter Streamer notebook.

Next, I cleaned and standardized the tweets in order to utilize them as effectively as possible.  This lead to some topic modeling with LDA and context toping modeling with Word2Vec.  

This allowed me to learn about the main topics and trends that users were consistently talking about.  Once I learned this information, I used a couple clustering methods to separate the tweets into unique clusters.  Finally, I did some sentiment analysis on these main topics, and compared these sentiments across different clusters, to see how positive or negative users feelings are towards these popular talking points.  All of these steps can be seen in the final project notebook.

Further improvements and analysis will be done.
