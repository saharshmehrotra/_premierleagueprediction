# Premier League Table Prediction

## Introduction

In the realm of global football, the English Premier League stands out as a beacon of quality and competition. It boasts top-tier teams and is renowned for its unpredictability and passionate matches. This project aims to leverage data analysis to predict Premier League match outcomes, providing clubs with insights to gain a competitive edge.

## Problem Statement

The goal is to create a dynamic Premier League table using predictive analytics, enabling clubs to forecast match outcomes and position themselves for success.

## Dataset Description

Data was scraped from various sources, including head-to-head match results, individual player statistics, team statistics, and player ratings. These datasets provide comprehensive insights into team and player performance over the past two seasons.

## Data Collection and Preprocessing

Steps were taken to clean and preprocess the data, including removing unwanted columns, handling missing data, correcting garbage values, creating new columns for additional insights, label encoding and standardizing team names.

## Exploratory Data Analysis (EDA)

EDA was conducted to gain insights into team performance, player statistics and match factors such as venue. Visualizations were used to analyze correlations and trends within the data.

## Model Testing and Building

Various machine learning models were tested, including Random Forest Classifier, SVM, GBM, KNN and Gaussian Naive Bayes. Random Forest Classifier emerged as the best-performing model, with high accuracy, precision, recall and Jaccard Score.

## Model Deployment

The predictive model was deployed using Streamlit, creating a user-friendly web interface. Users can access live table predictions, team data and interactive EDA graphs.

## Conclusion

This project demonstrates the application of Python and machine learning techniques to predict Premier League match outcomes. While the model provides valuable insights, the unpredictable nature of football means that predicting winners remains a challenging task.

## Deployment Link

[Premier League Table Prediction](https://premier-league.streamlit.app/)

---

*Note: For detailed implementation and code, refer to the respective Python scripts and notebooks.*
