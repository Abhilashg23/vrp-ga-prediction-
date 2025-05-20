# Enhanced Regression Modeling for Short-Time Prediction of Genetic Algorithm Outcomes in Vehicle Routing Problems

This repository provides resources for a research project that leverages enhanced regression models to **predict the outcomes of Genetic Algorithms (GAs)** during their early execution stages for solving **Vehicle Routing Problems (VRPs)**. This approach significantly reduces computational time while maintaining accuracy.

---

## 📁 Contents

* `regression_ga_vrp_prediction.ipynb`: Main Jupyter Notebook containing:

  * Implementation of regression models
  * SHAP value analysis
  * Visualizations and performance evaluation
* `all_instances_data.csv`: Dataset with extracted features and GA outcomes used for model training and testing.
* `Vehicle Routing Problems_IEEE2.pdf`: Research paper outlining the methodology, experiments, and key findings.

---

## 📊 Problem Statement

While Genetic Algorithms are powerful solvers for VRPs, they can be computationally intensive. This project presents a **regression-based early prediction technique**, enabling faster estimation of GA outcomes based on partial execution data, helping reduce resource usage.

---

## 🧠 Methodology

* **Feature Extraction**:

  * Inputs such as route distance, customer demand, vehicle capacity, etc., are captured from early GA iterations.
* **Regression Models Used**:

  * Linear Regression
  * Ridge Regression with Cross-Validation (RidgeCV)
  * Random Forest Regressor
  * Stacked Ensemble (combining Ridge, Poisson, and Random Forest)
* **Visualization Tools**:

  * Residual plots, learning curves, and SHAP feature importance visualizations
* **Evaluation Metrics**:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)
  * Root Mean Squared Error (RMSE)

---

## 📈 Results

* The **Random Forest Regressor** achieved the **lowest MAE (\~1356)** among all models.
* Predictions were up to **\~1800x faster** than full GA executions.
* **SHAP analysis** and feature importance visualizations improved interpretability and model trust.

---

## 🚀 Getting Started

1. Clone the repository and open the main notebook:

   ```bash
   git clone https://github.com/your-repo-link
   cd your-repo-folder
   jupyter notebook regression_ga_vrp_prediction.ipynb
   ```

---

## 📝 Citation

If you use this code or dataset in your work, please cite the following:

> Abhilash G, Lakshmi K. R. — *Enhanced Regression Modeling for Short-Time Prediction of Genetic Algorithm Outcomes in Vehicle Routing Problems*, Chanakya University, Bengaluru.

---

## 📬 Contact

For queries or collaboration opportunities, reach out to:

* 📧 Abhilash G: [abhilashg.mca24@chanakyauniversity.edu.in](mailto:abhilashg.mca24@chanakyauniversity.edu.in)
* 📧 Lakshmi K. R.: [lakshmikr.mca24@chanakyauniversity.edu.in](mailto:lakshmikr.mca24@chanakyauniversity.edu.in)

---

## 📄 License & Data Availability

* This project is available for **academic and research use only**.
* **Data Access**: The GA input and output data used in this study can be accessed online at:
  [https://ubaya.id/vrp\_ga\_input\_output](https://ubaya.id/vrp_ga_input_output) (Accessed on 2 December 2023).

---
