# PRODIGY_DS_04

Objective:
Analyze Twitter text data to classify sentiments into Positive, Negative, or Neutral using VADER sentiment analysis.

Dataset:

twitter_training.csv – contains 4 columns:

Platform

User

OriginalSentiment

Text

Steps Performed:

Loaded dataset and assigned proper column names.

Cleaned text data and handled missing values.

Applied VADER (NLTK) sentiment analysis to create a PredictedSentiment column.

Visualized results:

Countplot for sentiment distribution

Pie chart for sentiment proportions

WordCloud for each sentiment category

Compared predicted sentiments with original labels using:

Accuracy Score

Classification Report

Confusion Matrix

Saved output with predictions to CSV.

Libraries Used:
pandas, matplotlib, seaborn, nltk, wordcloud, scikit-learn

Results:

Distribution of tweets by sentiment.

Insights from text patterns and word clouds.

Model evaluation metrics against original sentiment labels.
