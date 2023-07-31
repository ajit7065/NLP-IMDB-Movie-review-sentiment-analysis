# NLP-IMDB-Movie-review-sentiment-analysis

This is a sentiment classification project with IMDB moview review Dataset available on Kaggle It is a record of moview review available on IMDB website. Along with reviews, it contains sentiment of review negative and positive. Here it is posed as a binary classififcation problem. Suitable Exploratory Data Analysis has been done followed by modeling as follows

Bag of Words with Naive Bayes, Logistic regression, Decision tree, Random Forest, XGBoost
TFIDF with Naive Bayes, Logistic regression, Decision tree, Random Forest, XGBoost
Word 2 vec with Naive Bayes, Logistic regression, Decision tree, Random Forest, XGBoost
Multilayer perceptron with embedding layer, CNN and LSTM


Different techniques has given different recall values as follows


With BOW Logistic Regression gives best recall of  = 0.88

With TFIDF Logistic Regression gives best recall of  = 0.90

With Word2Vec Logistic Regression gives best recall of  = 0.88

Embedding layer with pretrained glove vectors(MLP) = 0.75 (Overfitting)

Embedding layer with pretrained glove vectors(CNN) = 0.85 (Overfitting)

Embedding layer with pretrained glove vectors(LSTM) = 0.86 (Overfitting)
