# Imdb_Review_Sentimentanalysis
Sentimental analysis using bag-of-words on IMDB reviews

IMDB dataset having 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification with 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using a classification algorithm.
For more dataset information, please go through the following link,
[http://ai.stanford.edu/~amaas/data/sentiment/](URL)

**In this notebook:**
- The Sentimental analysis is done using the Bag-of-Words (BOW) method.
- The data is preprocessed by using word tokenizer and TF-IDF Vectorizer from the python library module of nltk
- The model is selected through the validation technique of cross_val_score
- Logistic Regression gave the highest accuracy score of around 90%
