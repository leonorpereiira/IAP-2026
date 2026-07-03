# Probabilistic Modeling and Decision-Making for Sports Analytics

This project explores **Probabilistic Artificial Intelligence** techniques for predicting football match outcomes in the Portuguese league. It combines **Bayesian Networks**, **Naive Bayes classification**, **Conformal Prediction**, **Calibration Analysis**, **Bayesian Optimization**, and **Utility-Based Decision Making** to model uncertainty and support informed decisions.

## Overview
The objective of this project is not only to predict football match outcomes but also to quantify uncertainty and evaluate the practical usefulness of probabilistic predictions.

The project is divided into three main components:

- Bayesian Networks for probabilistic reasoning and inference
- Probabilistic classification and uncertainty quantification
- Utility theory and decision-making analysis

---

## Dataset

Historical football match data from the Portuguese league was collected and processed to extract relevant features, including:

- Team recent form
- Offensive performance
- Head-to-head dominance
- Betting market odds
- Home and away performance statistics

Feature engineering was performed using historical match information and football domain knowledge.

---

## Bayesian Networks

Two Bayesian Network structures were developed:

### Knowledge Engineering Approach

A manually designed Bayesian Network based on football domain expertise.

### Structure Learning Approach

A Bayesian Network automatically learned from data using:

- Hill Climbing
- Bayesian Information Criterion (BIC) Score

The learned network was analyzed through:

- D-Separation
- Conditional Independence
- Probabilistic Inference
- Parameter Learning (MLE and BDeu)

---

## Probabilistic Classification

### Naive Bayes

A categorical Naive Bayes classifier was trained to predict:

- Home Win (H)
- Draw (D)
- Away Win (A)

Performance was evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

### Logistic Regression

A Logistic Regression model was optimized using Bayesian Optimization and compared against the Naive Bayes classifier.

---

## Uncertainty Quantification

### Conformal Prediction

Conformal Prediction was applied to generate prediction sets with statistical coverage guarantees.

The following metrics were analyzed:

- Coverage
- Prediction Set Size
- Singleton Prediction Rate

This approach enabled explicit quantification of prediction uncertainty.

### Calibration Analysis

Probability calibration was evaluated using:

- Brier Score
- Log Loss
- Reliability Diagrams

Calibration techniques were applied to improve probability estimates and reduce overconfidence.

---

## Utility-Based Decision Making

The practical usefulness of the probabilistic predictions was evaluated through several decision-making strategies.

### Market Comparison

- Conversion of betting odds into implied probabilities
- Analysis of disagreements between the model and betting markets

### Reject Option

Predictions with low confidence were rejected and replaced with market-based decisions.

### Value Bets

Expected Utility Theory was applied to identify:

- Positive Expected Value (EV) opportunities
- Potential betting strategies

### Betting Simulation

A betting simulation was conducted to evaluate:

- Profitability
- Return on Investment (ROI)
- Long-term utility of model predictions

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- pgmpy
- Matplotlib

---

## Main Topics

- Probabilistic Artificial Intelligence
- Bayesian Networks
- Naive Bayes
- Uncertainty Quantification
- Conformal Prediction
- Probability Calibration
- Bayesian Optimization
- Utility Theory
- Decision Making Under Uncertainty

---

## Authors

Developed as part of the **Probabilistic Artificial Intelligence** course in the **BSc in Artificial Intelligence and Data Science** at the **University of Coimbra**.