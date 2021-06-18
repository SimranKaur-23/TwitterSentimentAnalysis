# Twitter Sentiment Analysis
  - This task was performed as an academic assignment on NLP.
  - performed sentiment analysis on twitter dataset.
  - the data was extracted from twitter API using tweepy module.
  - the tweets are divided into three - positive, negative, neutral. These tweets are divided based on sentiment analyzer scores.
  - these scores were calculated using TextBlob module.
  - performed EDA, visulaization and analysis on the tweets.
## A gist of what i did...
  - import the necessary libraries.
  - used twitter API to extract tweets.
  - defined functions which clean the tweets, apply sentiment to the tweets.
  - The user is asked to enter the keyword of tweets and number of tweets.
  - stored the tweets in tweet list.
  - stored positive, negative, neutral tweets in separate lists.
  - next, i converted these lists into separate dataframes.
  - plotted a pie chart for the tweets depending on their sentiments.
  - now our tweets dataframe conatins tweet and a sentiment as separate columns.
  - added positive, neutral, negative, compound scores of each tweet as sperate columns in dataframe.
  - created a function for word cloud and displayed the word cloud of all tweets, positive tweets, negative tweets, neutral tweets.  
  - added polarity and subjectivity for each tweets as separate column names in dataframe.
  - added word count and tweet length for each tweet as columns.
  - next i removed punctuations from tweets, removed stopwords, tokenized them and stemmed them and made separate columns for each in the dataframe.
  - next, i cleaned the tweets and applied Countvectorizer on these cleaned tweets.
  - made a separate dataframe for these count vectorized tweets and displayed the most used words.
  - made a function to convert the tweets to n-gram.
  - displayed the bi-grams and tri-grams of tweets on screen.
  - next, separated the training and testing data and applied sentiment analysis on logistic regression. Displayed the classification report for the same.
## How to get data from API?
 - To get the data from twitter API you have to make an account on twitter and then fill a form giving details about how you'll use the data. 
 - Then you have the access the consumer key, consumer secret, access token and access token secret
