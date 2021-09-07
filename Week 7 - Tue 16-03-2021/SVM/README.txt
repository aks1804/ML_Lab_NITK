Lab 7 - Akshat Nambiar - 181CO204

SVM on Image Classification

Dataset: Sklearn Digits Dataset

Metrics:

Classification Report for SVM: 
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        60
           1       0.97      1.00      0.99        73
           2       1.00      0.97      0.99        71
           3       1.00      1.00      1.00        70
           4       1.00      1.00      1.00        63
           5       1.00      0.98      0.99        89
           6       0.99      1.00      0.99        76
           7       0.98      1.00      0.99        65
           8       1.00      0.99      0.99        78
           9       0.99      1.00      0.99        74

    accuracy                           0.99       719
   macro avg       0.99      0.99      0.99       719
weighted avg       0.99      0.99      0.99       719


Confusion matrix:
[[60  0  0  0  0  0  0  0  0  0]
 [ 0 73  0  0  0  0  0  0  0  0]
 [ 0  1 69  0  0  0  0  1  0  0]
 [ 0  0  0 70  0  0  0  0  0  0]
 [ 0  0  0  0 63  0  0  0  0  0]
 [ 0  0  0  0  0 87  1  0  0  1]
 [ 0  0  0  0  0  0 76  0  0  0]
 [ 0  0  0  0  0  0  0 65  0  0]
 [ 0  1  0  0  0  0  0  0 77  0]
 [ 0  0  0  0  0  0  0  0  0 74]]

Accuracy = 99%


