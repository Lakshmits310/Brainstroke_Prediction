# Brainstroke Prediction
This project focuses on comparing the performance of different machine learning models in predicting brain stroke from the given unbalanced data.

## The aproach
- The data is highly imbalanced with high number of negative brain stroke cases as compared to the positive brain stroke cases, this leads to high biasedness in the model. This was what happened when we tried building a model on the original dataset.
- This brought in the need for approaching the issue in 2 ways : equally balanced dataset and slightly unbalanced dataset.
- 1. Created a dataset with equal number of positive cases and negative cases ( randomly chosen ).
  2. Created a dataset with slightly higher number of positive cases than the negative cases.

## Conclusion
Compared the performances of models in this 3 cases and found out that the confusion matrix showed a better performance in the latter 2 cases as compared to the original case.
