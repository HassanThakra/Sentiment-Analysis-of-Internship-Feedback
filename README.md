Sentiment Analysis of Internship Feedback
📋 Project Overview

InternSent is a machine learning project that analyzes internship feedback to understand overall sentiment (positive or negative).
It helps organizations identify satisfaction levels and areas that need improvement.

Objectives

Perform Exploratory Data Analysis (EDA) on intern feedback.

Build a Logistic Regression model using TF-IDF features for sentiment classification.

Visualize sentiment distribution, word frequencies, and model performance.

Predict sentiment on new unseen feedback.

Technologies Used

Python 3

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn (Logistic Regression, TF-IDF Vectorizer)

WordCloud (for visual text analysis)

Dataset

File: feedback_data.csv

feedback_id: Unique identifier

feedback_text: Text of intern feedback

sentiment: Target label → 1 = Positive, 0 = Negative

How to Run

Clone or download this repository.

Place your feedback_data.csv file in the project folder.

Open the Jupyter Notebook:

jupyter notebook InternSent_Assignment.ipynb


Run all cells from top to bottom.

Results

The model achieves strong performance in classifying positive vs. negative feedback.

WordClouds highlight common words in positive and negative reviews.

Insights can guide improvement in intern experience and mentorship.

