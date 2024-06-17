# Divyanshi_kanwar_DataHack

## Problem statement
Your goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

## Submission format
The format for the submission file is three columns: respondent_id, xyz_vaccine,
and seasonal_vaccine. The predictions for the two target variables should be float
probabilities that range between 0.0 and 1.0. Because the competition uses ROC
AUC as its evaluation metric, the values you submit must be the probabilities that a
person received each vaccine, not binary labels. As this is a multilabel problem, the
probabilities for each row do not need to sum to one.

## My Implemtation
- Handled missing value from the dataset:
    - dropped columns containing more than 50% missing value.
    - used mean for numarical data.
    - used most frequent (mode) for categorical data.

- Defined models:
   - Logistic Regression: for predicting probabilities in binary classification tasks.
   - MultiOutputClassifier:the problem involves predicting probabilities for multiple labels 

- Performed Cross-Validation
   - ROC AUC score is used to quantify the model's ability to rank predicted probabilities correctly.

- Calculated the Mean Cross-Validation Score
  

