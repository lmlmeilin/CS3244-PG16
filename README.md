# Sarcasm Detection in Reddit Comments by CS3244 PG16

## Overview
This project focuses on building a machine learning-based sarcasm detection models to analyze user comments on the subreddit r/worldnews r/news r/politics. By detecting sarcasm in textual data, the project aims to enhance the understanding of public sentiment, providing value to industries such as journalism, social media monitoring, and natural language processing (NLP) applications. 

---

## Dataset
The Kaggle dataset comprises labelled (sarcastic and non-sarcastic) comments scraped from Reddit, which may contain biases. Reddit comments are subjective opinions or reactions of users that may not be fact-checked. The dataset contains about 1 million sarcastic comments (1 million rows) and ten features. 

Dataset: https://www.kaggle.com/datasets/danofer/sarcasm

The `Datasets` directory contains:
- `sentiment.csv` and `sentiment_test.csv`: Processed datasets for model training and evaluation.
- `sentiment_bigram_final.csv`: Processed datasets with top 50 bigrams

---

## Exploratory Data Analysis (EDA)

The `EDA` directory includes Jupyter notebooks to explore sarcasm data across various domains:
- `Sarcasm EDA.ipynb`: General sarcasm exploration.
- Topic-specific EDA: 
  - `Sarcasm EDA (news).ipynb`
  - `Sarcasm EDA (politics).ipynb`
  - `Sarcasm EDA (worldnews).ipynb`

---

## Feature Engineering and Data Cleaning

The `Feature Engineering : Data Cleaning` directory contains:
- `Sarcasm Data Cleaning and Preprocessing.ipynb`: Preprocessing text for sarcasm analysis.
- - `Bigrams_Data_Cleaning.ipynb`: Preprocessing text for sarcasm analysis, but keeping the top 50 most common bigrams.

---

## Models

The `Models` directory includes implementations of the following machine learning algorithms:
- **Decision Tree**: `Decision Tree.ipynb`
- **K-Nearest Neighbors (KNN)**: `KNN.ipynb`
- **Logistic Regression**: `Logistic_Regression.ipynb`
- **Neural Network**: `Neural Network.ipynb`
- **Random Forest**: `Random_forest.ipynb`
- **Support Vector Machine (SVM)**: `SVM.ipynb`

---

## Team Members
Nguyen Huy Dat, A0258929H

Jeong Youngkyu, A0252154M

Odele Pang Kun Ting, A0245935W

Ethan Yeo Alsagoff, A0240231B

Low Mei Lin, A0240908E

Yap Yi Pin, A0258069R


