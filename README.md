# TB Classification

6 different classification models were tested based on accuracy, precision, recall, and AUC score
Optimization was performed for those that might have been needed or where time constraint was not an issue

Notably:
  - CNN performed the best overall with SVC coming in close second
  - Optimization of MLP and SGD led to minimal improvement
  - If high accuracy desired, use CNN model; if high precision desired, use SVC; if high recall needed, use CNN
  - Best AUC score belongs to RFC, but poor recall

For those curious, I also wrote a paper that details the process and explanations for each model used
