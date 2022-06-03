# Sentiment_Analysis
Sentiment Analysis: Understanding Social Sentiments on Twitter

Social media such as Twitter have
emerged as one of the primary channels of
communication as well as information sharing.
Tweets are an effective, concise and fast method to
share information such as general news, opinions,
personal updates, reviews amongst many other
things. Often, the public sentiment around certain
topics can be gauged by looking at the tweets on
those topics or any topic that is trending.
In this project, we are trying to assess the
sentiments of tweets,either negative or positive.
The dataset used is the Sentiment-140 dataset that
was sourced from Kaggle. We preprocessed the
data to convert the text into lower case, removed
noise such as punctuation, URLS and hashtags.
We then tokenized the text and lemmatized it. We
use Logistic Regression, Support Vector Machine,
Multinomial Naive Bayes, Adaboost and Random
Forest models with TF-IDF vectorization and
LSTM model with Word2Vec word embeddings.
The LSTM model with 78.95% accuracy and
86.96% test AUC score is our final selection as the
best performing model.


## LSTM Model Results

![image](https://user-images.githubusercontent.com/17857561/171776827-5fe9356f-dff8-44c0-91f3-7d53ce589dd7.png)
