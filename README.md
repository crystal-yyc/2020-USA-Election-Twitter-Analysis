## NLP_Twitter_Analysis_on_2020-USA-Presidential_Election

* The data can be downloaded from the kaggle: https://www.kaggle.com/manchunhui/us-election-2020-tweets
* Different algorithms have been used to analyze the sentiment analysis and topic modeling
* "twitter2.ipynb" notebook includes data preprocessing, polarity score comparison based on Textblob and nltk SentimentIntensityAnalyzer (SIA), and sentiment analysis based on SIA modeling.
* "Topic.ipynb" notebook includes different topic modeling algorithm trials: sklearn NMF, sklearn LDA, Gensim with different POS tags of "nouns", "nouns & adj" et al. After the best topics are extracted, the donimant topic has been assigned back to each tweet. 
* "Bigram.ipynb" and "Bigram8.ipynb" include using bigram algorithm for topic modeling. 
