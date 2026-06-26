# ModelOptimization
# AI & ML Internship – Task 2
## Feature Engineering, Model Optimization & Performance Comparison
**Maincrafts Technology**

### Objective
Built an enhanced House Price Prediction system using the California Housing Dataset.
Trained and compared 3 regression models to select the best performer.

### Models Used
- Linear Regression (Baseline)
- Ridge Regression (L2 Regularization)
- Decision Tree Regressor (max_depth=5)

### Results
| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7455 | 0.5758 |
| Decision Tree | 0.7242 | 0.5997 |

### Best Model: Decision Tree Regressor
Achieved lowest RMSE and highest R² by capturing non-linear patterns in data.

### Tools
Python, Jupyter Notebook, scikit-learn, pandas, matplotlib, seaborn
