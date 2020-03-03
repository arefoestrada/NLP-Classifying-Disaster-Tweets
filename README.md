# NLP: Classifying Disaster Tweets

This repository was made to predict whether a tweet is discussing about a disaster or not. To commence the process, train dataset - which has been classified into disaster or non-disaster tweet - was separated into two different dataset (train and test dataset) to create an accurate model. The tweets were then extracted from each dataset and vectorized with Tfidf. The model utilized Multinomial Naive Bayes classifier to predict the tweet.

After the model performed classification in the train's test dataset, it produced 80.04% accuracy, which is quite accurate. The real test dataset were then tested with the model to determine the tweet classification (disaster or non-disaster).

## Author

* **Arefo Estrada** - *Initial work* - [arefoestrada](https://github.com/arefoestrada)