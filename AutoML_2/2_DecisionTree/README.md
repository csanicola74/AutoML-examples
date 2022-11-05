# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: mse
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

4.5 seconds

### Metric details:
| Metric   |       Score |
|:---------|------------:|
| MAE      |   38.0484   |
| MSE      | 2175.88     |
| RMSE     |   46.6463   |
| R2       |   -0.358866 |
| MAPE     |    0.162539 |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (age <= 61.5) and (exng <= 0.5) and (thall > 1.5) then response: 238.33 | based on 109 samples

if (age <= 61.5) and (exng > 0.5) and (caa <= 1.5) then response: 246.51 | based on 49 samples

if (age > 61.5) and (thalachh <= 150.5) and (oldpeak <= 3.45) then response: 245.774 | based on 31 samples

if (age <= 61.5) and (exng > 0.5) and (caa > 1.5) then response: 285.727 | based on 11 samples

if (age > 61.5) and (thalachh > 150.5) and (oldpeak <= 0.7) then response: 269.7 | based on 10 samples

if (age > 61.5) and (thalachh > 150.5) and (oldpeak > 0.7) then response: 353.778 | based on 9 samples

if (age <= 61.5) and (exng <= 0.5) and (thall <= 1.5) then response: 198.5 | based on 6 samples

if (age > 61.5) and (thalachh <= 150.5) and (oldpeak > 3.45) then response: 175.5 | based on 2 samples





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
