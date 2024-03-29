# Toxic_Comments_Kaggle

* Input
  * glove.840B.300d.txt: GloVe (Global Vectors for Word Representation), obtainable from [GloVe](http://nlp.stanford.edu/data/glove.840B.300d.zip)
  * train.csv: training data
  * test.csv: test data
  * test_labels.csv: test labels for toxic comments toxicity
  * sample_submission.csv: sample submission form for Kaggle score. Used to generate [submission.csv](submission.csv) and [submission_LSTM_1DCNN.csv](submission_LSTM_1DCNN.csv)
  
* Code
  * EDA.ipynb: notebook with data exploration, corpus cleaning, feature engineering and Logistic Regression with baseline Naive-bayes SVM classifier model
  * main.ipynb: Simple logistic Regression model
  * LSTM_1DCNN.py: Toxic Comment classification using LSTM and 1D-CNN model
  * xgb-baseline-with-feature-engineering: Multi-label classification using XGBoost and feature engineering. Notebook runs on Kaggle [here](https://www.kaggle.com/code/jinhongyong/xgb-baseline-with-feature-engineering)
