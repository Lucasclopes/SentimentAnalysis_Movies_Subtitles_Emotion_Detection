# Sentiment Analysis: Detecting Emotions from movie subtitles

**Summary:** Detecting emotions in english movie subtitles, where the input is a sentence (the subtitle). 

**Keywords**: Python, Natural Language Processing, Emotion Detection, SVM, BERT, NN

## Important libraries and packages 
- pandas, numpy
- seaborn, matplotlib
- nltk (Natural Language Toolkit) - for ngrams, stopwords, lemmatizing and stemming
- sklearn

## Data
A randomly sampled subset of the XED dataset for multiclass emotion detection, which consists of English movie subtitles from OPUS corpus1 annotated with emotional polarity and discrete emotions,  was used.

The XED dataset originally contains multilabel annotations for discrete emotions, but to keepthings simpler, a single label dataset was provided, extracted from the English dataset, where each example looks like this:
- You will help our medical research and thereby saving thousands of lives . 8

The sentence and the label are separated by a tab character (\t), and the labels are mapped as follows:
- 1: Anger
- 2: Anticipation
- 3: Disgust
- 4: Fear
- 5: Joy
- 6: Sadness
- 7: Surprise
- 8: Trust

## Steps
- ### Importing the the data
- ### Oversampling and Undersampling
- ### N-grams and word importance with TF-IDF
- ### Modelling(KNN Classifier, Neural Networks, Naive Bayes, SVM, Gradient Boosting, BERT)

Note: The best performing model ended up being BERT, an open-source machine learning framework for natural language processing, that runs on google colab. Because of that, the steps regarding this model were taken on that platform and then download into a ipynb file (bertmodel_colab), also present in this repository.





