# twitter-sentiment-analysis
In this binary classification project I am using Multinomial Naive Bayes on Vectorised Twitter data to classify Tweets as being Positive or Negative.
- Data is vectorised using Bag-Of-Words with common Stop words
- After that a Naive Bayes (Gaussian) is trained on the data.
- This trained model is then saved (pickled).
- At test-time this model is loaded to classify new data.

