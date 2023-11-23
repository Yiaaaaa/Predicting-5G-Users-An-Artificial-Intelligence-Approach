# Predicting 5G Users: An Artificial Intelligence Approach

## Abstract:

This project aims to explore and solve real-life problems using artificial intelligence (AI) techniques implemented in the Python programming environment. The model is based on 80,000 records and 60 features to predict whether a given sample belongs to a 5G user. The project involves training and comparing multiple AI models and analyzing their performance using the Area Under the Curve (AUC) evaluation metric. 

## Introduction:

The rapid growth of 5G technology has resulted in a significant increase in the number of 5G users worldwide.This project aims to leverage AI algorithms to predict 5G users based on data related to various user-related features.

## Methods:

1. Data Preprocessing: The dataset, consisting of 60 fields, including categorical and numerical features, is first preprocessed to handle missing values, encode categorical variables, and normalize numerical features.
2. Feature Selection: Relevant features are selected to enhance the models' predictive performance and reduce computational complexity.
3. Model Training: Five algorithms (Logistic Regression, Decision Trees, Random Forest, Neural Networks, LightGBM) are trained on the preprocessed dataset.
4. Model Evaluation: The trained models are evaluated using the AUC metric to assess their performance in predicting 5G users.
5. Model Comparison and Analysis: The results obtained from different models are compared and analyzed to identify the most effective approach.

## Results and Discussion:

Result: The experimental results indicate that the implemented AI model, Random Forest, performs well in predicting 5G users. It has a higher AUC value and is more suitable for modeling in this experiment.

Discussion: There are some areas for optimization: 

Feature selection: By filtering the features and retaining those that are more important for the classification task, it is possible to improve the accuracy and generalization ability of the model. 

Parameter tuning: By adjusting the hyperparameters of the model, such as learning rate, tree depth, minimum samples for node splitting, etc., it is possible to improve the performance of the model. 

Using ensemble methods: It is possible to improve the accuracy and robustness of the model by integrating multiple models through methods such as voting, averaging, or stacking.

## Conclusion:

The project successfully utilized AI technology to predict 5G users. By leveraging relevant data and conducting accurate predictions, potential 5G users were identified. 
