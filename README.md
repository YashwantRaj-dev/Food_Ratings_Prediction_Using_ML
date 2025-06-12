# Food_Ratings_Prediction_Using_ML

This project was developed as part of a Kaggle Machine Learning contest where the task was to predict food ratings based on multiple key performance indicators (KPIs) such as user engagement, recipe details, comments, and more.

Goal
To build a robust ML model capable of accurately predicting food ratings and exploring user engagement metrics that influence recipe ratings.

Problem Statement :
Given a dataset with the following features:
UserReputation, ThumbsUpCount, ReplyCount, RecipeReview, BestScore, etc., the goal was to predict the Rating a user would give to a recipe.

Below were the steps involved in the code :
(i) Exploratory Data Analysis (EDA):
- Analyzed key metrics and trends to understand data distribution and correlations.
- Performed visualizations to interpret user behavior and rating distribution.

(ii) Data Preprocessing:
- Handled missing values and outliers.
- Converted timestamps into a readable datetime format.
- Dropped irrelevant or highly sparse columns to improve model performance.

(iii) Feature Engineering:
- Extracted useful features from timestamp and review columns.
- Encoded categorical features where necessary.

(iv) Pipeline Building:
- Constructed preprocessing pipelines using scikit-learn to ensure consistent transformations.
- Included steps like scaling, encoding, and model training within a single pipeline.

(v) Model Building & Evaluation:
- Trained and tested multiple models including:
✅ Random Forest (Best Performer)
✅ Logistic Regression
✅ Decision Tree
- Compared performance based on accuracy and cross-validation scores.

(vi) Final Prediction and Submission:
- The best model (Random Forest) was used to generate predictions on the test dataset.
- Created a submission .csv file for Kaggle evaluation.

Technologies Used :
- Python
- Pandas, NumPy
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (ML modeling and pipelines)

Outcome
The Random Forest Classifier achieved the highest accuracy and was selected for final predictions.
A .csv file was generated as a submission for the Kaggle leaderboard.
