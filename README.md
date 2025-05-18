# Enhanced Regression Modeling for Short-Time Prediction of Genetic Algorithm Outcomes in Vehicle Routing Problems

This repository contains resources for a project that uses enhanced regression models to predict the outcomes of Genetic Algorithms (GAs) in solving Vehicle Routing Problems (VRP), based on early GA behavior.

## 📁 Contents

- `regression_ga_vrp_prediction.ipynb`: Main Jupyter notebook with regression models, SHAP analysis, and visualizations.
- `all_instances_data.csv`: Dataset with features and GA outcomes used for training and testing models.
- `Vehicle Routing Problems_IEEE2.pdf`: Research paper detailing methodology, experiments, and findings.

## 📊 Problem Statement

Genetic Algorithms are effective for solving VRPs but are often time-consuming. This project introduces a regression-based approach that predicts the outcome of a GA early in its run to reduce computational load.

## 🧠 Methodology

- Feature extraction from VRP-GA runs (e.g., distance, demand, vehicle capacity).
- Use of multiple regression models including:
  - Linear Regression
  - Random Forest
  - RidgeCV
  - Stacked Ensemble (Ridge + Poisson + RF)
- Visualization tools:
  - Residual plots, feature importances, learning curves, etc.
- Evaluation metrics: MAE, MSE, RMSE

## 📈 Results

- **Random Forest** had the lowest MAE (~1356).
- Predictions were made ~1800x faster than full GA runs.
- Feature importance and SHAP values enhanced explainability.

## 🚀 Getting Started

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook regression_ga_vrp_prediction.ipynb
   ```

## 📝 Citation

If you use this code or data, please cite the original authors:
> Abhilash G, Lakshmi K. R. — *Enhanced Regression Modeling for Short-Time Prediction of Genetic Algorithm Outcomes in Vehicle Routing Problems*, Chanakya University, Bengaluru.

## 📬 Contact

For any questions or collaboration:
- Email: abhilashg.mca24@chanakyauniversity.edu.in
- Email: lakshmikr.mca24@chanakyauniversity.edu.in

---

**License**: For academic and research use only.
