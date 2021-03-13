# Unit 11—Risky Business

![Credit Risk](Images/credit-risk.jpg)

## Background

Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. IN this assignment i will be using the Machine learning models and techniques to predict credit risk.

Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so i will be using different techniques for training and evaluating models with imbalanced classes. i used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

Resampling
Ensemble Learning

1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)

In this assignment i was able to answer the following questions

### 1. Resampling

> Which model had the best balanced accuracy score?
* The RandomOverSampler model predicts the highest balanced accuracy score. This model gives us the highest probability of correct calls or correct predictions for credit risk.
> Which model had the best recall score?
* The RandomOverSampler model has the best Recall score. This model will give us the highest actual positive samples that are correct.
> Which model had the best geometric mean score?
* The RandomOverSampler model has the best geometric mean score.

### 2. Ensemble Learning

> Which model had the best balanced accuracy score?
* The EasyEnsembleClassifier model predicts the highest balanced accuracy score. This model gives us the highest probability of correct calls or correct predictions for credit risk.
> Which model had the best recall score?
* The EasyEnsembleClassifier model predicts the highest balanced accuracy score. This model will give us the highest actual positive samples that are correct.
> Which model had the best geometric mean score?
* The EasyEnsembleClassifier model predicts the highest geometric mean score.
> What are the top three features?
* total_rec_prncp','total_pymnt','total_pymnt_inv are the top 3 features in the model predictions.

---

### Hints and Considerations

For the ensemble learners, use 100 estimators for both models.

---

