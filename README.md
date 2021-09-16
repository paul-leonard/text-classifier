# text-classifier
A machine learning project to determine positive or negative sentiments in English sentences.

## Lab Submission Pull Requests
[Lab37: Machine Learning Intro](https://github.com/paul-leonard/text-classifier/pull/1)

## Release Info
**Author**: Paul Leonard
**Version**: 0.9.0

## Overview
A sentiment analysis is completed using sentences from yelp, amazon, and imdb reviews, a machine learning model is trained to identify positive or negative reviews as a demonstration of natural language processing (NLP).

## Architecture
Beginning with the overall corpus, the sentences from the reviews are tokenized and used to create a feature vector.  Due to the large vocabularly included in this Bag-of-words (BOW) model, a sparse matrix is used to represent the data.  To prevent overfitting, a test/trainsplit from scikit-learn is utilized.  A logistic regregression is performed independently on each of the three source datasets and their accuracy calculated.  Libraries used include pandas, numpy, and scikit-learn.

## Change Log
**0.9.0** 12-29-2020 - Initial beta release
**1.0.0** 12-TBD-2020 - Initial release

## Credits and Collaborations
- [Real Python's Practical Text Classification With Python and Keras Tutorial](https://realpython.com/python-keras-text-classification/)
- [UCI: Sentiment Labelled Sentences Data Set](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences)
- [pandas.concat](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.concat.html)
