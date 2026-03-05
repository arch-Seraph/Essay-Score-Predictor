# Essay Scoring Prediction using NLP

## Overview

This project builds a machine learning system to automatically evaluate argumentative student essays.
The model predicts the **holistic score**, **score band**, and provides insights into **writing proficiency and discourse structure**.

The dataset contains over **285,000 discourse elements** extracted from student essays.

## Objectives

* Predict **Holistic Essay Score** (Regression)
* Predict **Score Band** (Classification)
* Analyze **writing components and discourse structure**
* Evaluate **fairness across demographics**

## Dataset

The dataset includes:

* Essay text
* Discourse elements (Claim, Evidence, Rebuttal)
* Discourse positions within essays
* Writing prompt information

Due to dataset size, only a **sample dataset** is included in this repository.

## Feature Engineering

Key features extracted:

* Word count
* Sentence count
* Average word length
* Discourse type counts
* Discourse structure patterns
* TF-IDF text features
* Dimensionality reduction using SVD

## Models Used

### Regression

* Random Forest Regressor
* Gradient Boosting
* Ridge Regression

### Classification

* Logistic Regression
* Random Forest
* XGBoost

## Evaluation Metrics

Regression:

* MAE
* RMSE
* R² Score

Classification:

* Accuracy
* F1 Score
* Confusion Matrix

## Fairness Evaluation

Performance was evaluated across:

* Gender
* Grade level
* Writing prompts

Metrics include:

* Demographic parity
* Equal opportunity difference

## Model Interpretability

Feature importance and model explanations were analyzed using:

* SHAP values

## Results

The Gradient Boosting model achieved the best performance with strong predictive accuracy and balanced fairness across groups.

## Project Structure

See repository folders for notebooks, source code, models, and results.

## Future Improvements

* BERT based embeddings
* Fine-tuned transformer models
* Essay coherence modeling
* Deployment as a scoring API
