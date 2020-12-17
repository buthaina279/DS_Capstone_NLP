# Capstone project for Data Science course with Misk Academy

# Author: Buthaina Alshareef
# Date: 14/12/2020


# Objective:

- Analyze the sentiment of tweets on eleven international airlines.

- Extracting features that represent travelers feelings about the services that is provided by each airline.

- Predicting the sentiment using the extracted features from the tweets and all the airlines.


# In this repo there are five Jupyter notebooks:

- Collect_clean:
    - In this notebook I collected the data set for 11 international airlines using twitter API which is offered the tweets for 7 days only.
    - remove duplicated rows
    - NLP text pre-processing
    
- Classification:
   - Sentiment Analysis using TextBlob 
   - get the words for positive and negative sentiment just to understand the reason for the classification
   
- Extract_features:
  - Extract features from each tweet and create a column for each feature, this represented by 0 (did not find the feature) and 1 (found the feature).

  
- EDA (Exploratory Data Analysis):
  - EDA on the airline dataset
  - search for specific words to get some features about all the airlines 
  - visualize the features for the airlines with the sentiment
  
- ML(Machine Learning):
  - preprocessing 
   - traget is the sentiment
  - Apply random forest and logistic regression 
  - SMOTE to handle the imbalance in the dataset
 
