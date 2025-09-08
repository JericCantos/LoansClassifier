# LoansClassifier
Given a dataset containing loans that are approved or declined, are we able to predict whether a new loan would be approved?

In this project I conduct EDA, data cleaning, and build a pipeline, and evaluate different algorithms across multiple configurations to answer the question: which model would be the best to use for this purpose?

# Results

Logistic regression minus the `dependents` columns optimizing for weighted F1-score would be my choice for the following reasons:
- comparable performance with the "Best" model
- more easily explainable
- errs on the side of class 1, giving it more "heart".

To see how I came about this conclusion, check out the notebook.