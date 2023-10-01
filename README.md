# Spotify-Hit-Prediction
## SOURCES
The Dataset is orignally derived from the website Kaggle.com you can access it from here https://colab.research.google.com/drive/1o_GxXAg1AvyuLSLhqld-7b7N-dOsd1t9#scrollTo=itKF1GJtjJE2&line=2&uniqifier=1

## PROBLEM APPROACH
The type of dataset and the problem is a classic supervised binary classification. We want to build a machine learning model to predict whether a song will be a 'Hit' or a 'Flop', using data from Spotify. We start by inspecting and visualizing the dataset, then clean and transform the data before building and testing multiple models (LR, RFC, GaussianNB, KNN, LDA, SCV, CARD). We evaluate the models using metrics like accuracy, precision, recall, and AUC-ROC, then analyze their performance by Confusion Matrix and Classification Report to select the two best models, Random Forest Classifier and SVM. After that, we modify the threshold of the Random Forest Classifier model and evaluate its performance on the test set. Finally, we check the performance of the final model with 'made-up' information.
