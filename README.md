# NLP problems

In this repository I will upload regularly my solutions to NLP oriented problems, mostly coming from Kaggle Datasets.

1) Spam-Classification

We create here a simple spam classifier, by using the kaggle dataset 'SMS Spam Collection Dataset' (https://www.kaggle.com/uciml/sms-spam-collection-dataset).

We achieve accuracy over 98% percent on the test set.

2) Twitter Sentiment Analysis

Here we play with the Kaggle Dataset "Sentiment140 dataset with 1.6 million tweets" (https://www.kaggle.com/kazanova/sentiment140). 

We proceed through the preprocessing steps of cleaning the text, tokenizing, lemmatizing and other steps. Then we use an XGBooster Classifier in order to classify properly the text. We achieve the score of 77.15%

Some Technical notes: Training takes a lot of time (around 6hours) on my laptop (4GB RAM, 4 cpu i7 cores). Therefore in case someone wants to run the script, it is possibly better to use the model that I uploaded.
