# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 4
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.7 seconds

### Metric details
|           |         0 |   1 |   2 |   3 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |  0.465517 |   0 |   0 |   0 |   0.465517 |    0.116379 |       0.216706 |   1.22601 |
| recall    |  1        |   0 |   0 |   0 |   0.465517 |    0.25     |       0.465517 |   1.22601 |
| f1-score  |  0.635294 |   0 |   0 |   0 |   0.465517 |    0.158824 |       0.29574  |   1.22601 |
| support   | 27        |  10 |  16 |   5 |   0.465517 |   58        |      58        |   1.22601 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |               27 |                0 |                0 |                0 |
| Labeled as 1 |               10 |                0 |                0 |                0 |
| Labeled as 2 |               16 |                0 |                0 |                0 |
| Labeled as 3 |                5 |                0 |                0 |                0 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
