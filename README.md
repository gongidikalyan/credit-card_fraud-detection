# Credit Card Fraud Detection System

## Abstract

Credit card fraud has become a major concern in the digital payment ecosystem. This project aims to develop a machine learning-based fraud detection system capable of identifying fraudulent transactions from a large dataset of credit card transactions. Since fraudulent transactions are rare compared to legitimate transactions, the dataset is highly imbalanced. To address this issue, oversampling techniques were applied before training the model.

## Introduction

With the rapid growth of online payments and digital banking, fraudulent activities have increased significantly. Traditional fraud detection methods often fail to identify new fraud patterns. Machine learning techniques can analyze transaction data and detect suspicious activities more effectively. This project focuses on building a predictive model that classifies transactions as either legitimate or fraudulent.

## Objectives

* Detect fraudulent credit card transactions using machine learning.
* Handle class imbalance in the dataset.
* Train and evaluate a classification model.
* Improve fraud detection accuracy and reliability.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Imbalanced-Learn
* Matplotlib

## Methodology

### Data Collection

The project uses a publicly available credit card transaction dataset containing both legitimate and fraudulent transactions.Dataset is collected in the kaggle creditcard.csv file

### Data Preprocessing

* Loaded the dataset.
* Checked for missing values.
* Separated features and target variables.
* Scaled and prepared data for training.

### Handling Imbalanced Data

Since fraudulent transactions represent a very small portion of the dataset, Random Oversampling was used to balance the classes and improve model performance.

### Model Training

The balanced dataset was split into training and testing sets. Machine learning algorithms were trained to classify transactions as fraudulent or legitimate.

### Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

## Results

The fraud detection model successfully identified suspicious transactions with improved performance after balancing the dataset. The evaluation metrics showed that the model can effectively distinguish between legitimate and fraudulent transactions.

## Real-World Applications

* Banking fraud prevention
* Online payment security
* Financial transaction monitoring
* Risk management systems

## Conclusion

This project demonstrates the application of machine learning in detecting credit card fraud. By addressing class imbalance and training predictive models, the system can help financial institutions reduce fraud-related losses and improve transaction security.


