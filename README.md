# User Tweets Analysis

I utilized unsupervised machine learning techniques to analyze daily tweets directed towards major news sources for the week days of Nov 12 to Nov 16 (2018).  Note: This was one week following the 2018 Mid-term Elections. 

The first step of the process involved using Tweepy to stream about 20,000 tweets containing the key words CNN, Fox News, Economist, and Wall street Journal.  These steps are detailed in the Twitter Streamer (.ipynb) notebook.

Next, I cleaned and standardized the tweets in order to utilize them as effectively as possible.  This lead to some topic modeling with Latent Dirichlet Allocation (LDA).  It became evident that the news tweets throughout this week were hovering around a few major topics.  Since tweets were gathered shortly after the Midterm Elections, there were a few political figures that were consistent talking points throughout this week.  Word2Vec context modeling was also utilized to capture meaning and context throughout tweets.

Once I learned this valuable information, I used a couple clustering methods to separate full tweets into unique clusters.  Finally, I did some sentiment analysis on these main topics, and compared these sentiments across different clusters, to see how positive or negative users feelings are towards these popular talking points.  All of these steps can be seen in the final project notebook.

I developed a web page using HTML and CSS, to encapsulate some of my findings throughout this analysis into visuals.  The code can be found in the Atom text editor (.py) script in this repository.  The public web page will be up and running shortly.
