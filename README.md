# Solar Prediction Project

## Purpose
This repository contains multiple machine learning models for predicting solar power output (Output Power (kW)) based on historical weather and energy data. Each model has a baseline version (default parameters) and a tuned version (with hyperparameter optimization).

## Models Included
- Random Forest
- XG-Boost

## Folder Structure
```bash
SolarPrediction/
│── RandomForest/
│ ├── rf_baseline.ipynb
│ └── rf_tuned.ipynb
│── XGBoost/
│ ├── xgb_baseline.ipynb
│ └── xgb_tuned.ipynb

```


## Results (example outputs)

| Model                     | Version    | MAE       | RMSE    | R²    |
|---------------------------|------------|-----------|---------|-------|
| Random Forest             | Baseline   | 0.379     | 2.81    | 0.99  |
| Random Forest             | Tuned      | 0.3399    | 2.61    | 0.99  |
| XGBoost                   | Baseline   | 11.281    | 406.14  | 0.99  |
| XGBoost                   | Tuned      | 9.78      | 314.35  | 0.99  |




