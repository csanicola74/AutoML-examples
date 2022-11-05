# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

3.1 seconds

### Metric details:
| Metric   |         Score |
|:---------|--------------:|
| MAE      |   31.3677     |
| MSE      | 1607.53       |
| RMSE     |   40.094      |
| R2       |   -0.00392512 |
| MAPE     |    0.136148   |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |   Learner_1 |
|:----------|------------:|
| thall     |  0.169459   |
| age       |  0.162651   |
| exng      |  0.161141   |
| thalachh  |  0.114071   |
| slp       |  0.0711428  |
| fbs       |  0.0570083  |
| trtbps    |  0.048487   |
| caa       |  0.00736213 |
| oldpeak   | -0.0292982  |
| cp        | -0.0378626  |
| intercept | -0.0631988  |
| output    | -0.0838482  |
| restecg   | -0.140859   |
| sex       | -0.242367   |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
