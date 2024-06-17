# Divyanshi_kanwar_DataHack

## Problem statement
Your goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

## Implemtation
- Handled missing value from the dataset:
    - used mean for numarical data.
    - used most frequent (mode) for categorical data.
- Defined models:
   - Logistic Regression: for predicting probabilities in binary classification tasks.
   - MultiOutputClassifier:the problem involves predicting probabilities for multiple labels 

- Performed Cross-Validation

- Calculated the Mean Cross-Validation Score
