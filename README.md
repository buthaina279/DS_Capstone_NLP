# Capstone project for Data Science course with Misk Academy

# Author: Buthaina Alshareef
# Date: 14/12/2020


# Objective:

Analyze how travelers expressed their feelings on Twitter in the last 7 days. In addition, predict the airline name from some features that were extracted from the tweets.


# In this repo there are four Jupyter notebooks:

- Collect_munging:
    - In this notebook I collected the data set for 11 international airlines using twitter API which is offered the tweets for 7 days only.
    - remove duplicated rows
    - NLP pre-processing
    
- Classification:
   - Sentiment Analysis using TextBlob 
   - get the words for positive and negative sentiment just to understand the reason for the classification
  
- EDA (Exploratory Data Analysis):
  - EDA on the airline dataset
  - search for specific words to get some features about all the airlines 
  - visualize the features for the airlines
  
- ML(Machine Learning):
  - Extract features from each tweet and create a column for each feature, this represented by 0 (did not find the feature) and 1 (found the feature).
  - preprocessing using OneHotEncoder
  - Apply ML that handle both Multiclass classification and imbalanced dataset
  - predictors are all features with likes of the tweets and sentiment
  - traget is the airline
