# Predicting the Tendency of Depression from Twitter Posts
This project focuses on analyzing Twitter text data to predict depression tendencies using machine learning techniques. The goal is to build and evaluate models that can classify text based on mental health indicators.
## Problem 
Mental health issues such as depression are increasingly reflected in social media activity. This project aims to develop a machine learning model that can detect depression tendencies from Twitter posts.
## Dataset
- Source: [https://www.kaggle.com/datasets/infamouscoder/mental-health-social-media]
- Type: Text data (Twitter posts)
- Target: Depression tendency (depressed / not depressed)
## Methodology
### Data Preprocessing
- Text cleaning (remove punctuation, stopwords, URL, Emoji)
- Tokenization using NLTK
### Feature Engineering
- TF-IDF vectorization
- Feature selection to improve model performance
### Models Used
- Logistic Regression
- XGBoost
- MLPClassifier
## Results
- Best model: MLPClassifier (Accuracy 0.74, F1-Score 0.74)
- Low overfitting (train-test gap: 0.03)
## Tools
- Python
- Pandas, NumPy
- scikit-learn
- NLTK
- Matplotlib
