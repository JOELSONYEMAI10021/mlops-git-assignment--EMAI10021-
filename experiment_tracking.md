## Manual Experiment Tracking Table

| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|---------------|------------|-----------------|---------------------|------------------|-----------------|-----------|-----------|
| EXP-01 | Decision Tree | Default | None | All features | 80/20 |  |  |
| EXP-02 | Decision Tree | Max depth = 5 | Scaling | Selected | 80/20 |  |  |
| EXP-03 | Random Forest | n_estimators=100 | Scaling | Selected | 80/20 | 0.86 | 0.90 |
| EXP-04 | Random Forest | n_estimators=200 | Scaling + Encoding | Selected | 80/20 | 0.89 | 0.93 |

