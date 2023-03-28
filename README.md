# T20I Prediction Model

## Introduction

Cricket is a game of uncertainty where any team can turn the game on its head in a matter of
minutes. The unpredictability of T20 cricket makes it even more exciting, with teams needing to make
quick decisions and adapt to changing circumstances. With the growing popularity of T20 cricket,
there is an increasing demand for accurate predictions of the final score of a match.

This T20 Score Prediction Model uses advanced machine learning algorithms to predict the final score
of a T20 match based on various factors such as the team's performance history, the playing grounds,
and the weather forecast. The model has been trained on a large dataset of historical T20 matches
and tested extensively to ensure accurate and reliable predictions.

With this model, cricket enthusiasts can get a better understanding of the possible outcome of a
match and make informed decisions while betting or playing fantasy cricket. The T20 Score Prediction
Model is designed to be user-friendly and easy to use, even for those who may not be well-versed in
machine learning.

## Recommended Modules

This module requires:

-   Numpy

-   Pandas

-   SafeLoad

-   Tqdm

-   Pickle

-   SciKit

-   XGBRegressor

-   Pipeline

-   StreamLit

## Installation

You need to have atleast Python 3.8 and all of the above modules for this model.

## How it's made?

1. I have taken a dataset of all the T20 international games from Kaggle. You can find the DataSet
   on
   "https://www.kaggle.com/datasets/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s"
2. First I have extracted the Data as it is Yaml files and created a new Dataset. I then created a
   Pickle file for that dataset and named "dataset_level1".
3. Then I created features for the "dataset_level1" file and pickled the new featured file named
   "dataset_level2".
4. Then I trained the model using diffrent techniques with XGBRegressor being the most accurate.
5. Then I created the final Pickle file "pipe" which is the trained model.
6. Then I created a fairly simple WebApp using StreamLit.
7. It is Uploaded on StreamLit Cloud. You can use it here
   "https://divyanshu1510-t20-score-predictor-app-ws5a2e.streamlit.app/"
8. The GitHub repo is at "https://github.com/Divyanshu1510/T20_Score_Predictor"
