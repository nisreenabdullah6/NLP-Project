# NLP & Classification of sentiment for Amazon luxury beauty product Reviews

## Introduction

In this project, we worked on a dataset which contains amazon luxury beauty product reviews. 
The aim of this project is to build an NLP model to find topics for each review. Along the way, we added the sentiment to build a classification model.


## Goals:

- Finding a topic for each review .
- Building a classification model to determine the type of sentiment weather its positive or negative.


# Methodology:

1- Loading the dataset.

2- EDA (cleaning and visualizing the data).

3- Building different topics Models.

4- choosing the best topic model

5- Building different classification Models.

6- choosing the model based on given best f1 to prediction.

## Dataset:

We used the dataset from  https://nijianmo.github.io/amazon/index.html#
The dataset contains  34278 reviews (rows) and 12 columns in total.

### Cleaning Data and preprocessing  :
- Removing Null 
- Strip columns name 
- Removing outliers 
- Removing unwanted columns 
- spellcheck for text review 
- Lemmatize for text review 
- Add new columns for date by induvial 
- Adding sentiment column 
- Adding new two columns for the review length and the words counts
- Covert text to CountVectorizer
- Covert text to TfidfVectorizer
- Feature Extraction Using svd , variance=.86


# Topic modelling :

- Frist, we used LSA model to try and find topics from the data, we tried with different numbers of topics from 2 to 10 but were not successful.
- then, we used LDA model to try and find topics instead of LSA, we tried with different numbers of topics from 2 to 10 but were not successful.
- Finally, we used Corex which gave us some sensible topics, but they were interlinked so much that we had to use anchors to try to force the model to focus on a sensible topics.


## Classification:

On this dataset we used different methods of classification to determine the type of sentiment weather its positive or negative :

    
- Descion Tree model.
- Logistic regression model.
- Random forest model.
- XGradient boosting model.
    

## Conclusion :

- Our best topic modeling is Corex
- Using over sampling to solve in balance data reduced  our f1 score 
- Our best classifier is XGBClassifier

## Future work:

- collect more reviews for different products.
- build a recommendation system for each user .
- Try  more classifiers .
- Build classification model to predict the topic of each review .


## Tools:



- Matplotlib.
- Seaborn.
- SQLite.
- Pandas.
- sklearn.
- json.
- dateTime.
- numpy.
- re.
- textBlob.
- String.
- nltk.
- pickle.




```python

```
