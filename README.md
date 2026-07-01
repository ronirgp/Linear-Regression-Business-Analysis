# Linear Regression Business Analysis

## Project Overview

This project demonstrates how to build a Linear Regression model using Python and Scikit-Learn to predict product sales based on marketing expenditure.

The project includes:

- Data exploration
- Data visualization
- Linear Regression model
- Predictions
- Model evaluation (RMSE and R²)
- Residual analysis
- Business interpretation

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## Dataset

The dataset contains the following business information:

- Date
- Region
- Product
- Units Sold
- Price
- Marketing Spend

---

## Model Results

| Metric | Value |
|--------|-------:|
| RMSE | 4.45 |
| R² Score | 0.2930 |
| Intercept (b₀) | 4.3475 |
| Slope (b₁) | 0.0147 |

---

## Business Interpretation

- Marketing Spend has a positive relationship with Units Sold.
- The model explains approximately **29%** of the variation in sales.
- The average prediction error is approximately **4.45 units**.
- The model provides an estimate of future sales based on marketing expenditure.
- Additional features such as weather, holidays, region, and product category could improve prediction accuracy.

---

## Project Structure

```
Linear-Regression-Business-Analysis/
│
├── data/
│   └── business_data.csv
│
├── images/
│   └── actual_vs_predicted.png
│
├── results/
│   ├── regression_results.csv
│   └── model_summary.txt
│
├── Linear_Regression_Business_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## What This Project Demonstrates

This project demonstrates:

- Data loading and exploration with Pandas
- Data visualization using Matplotlib
- Building a Linear Regression model
- Making predictions
- Evaluating model performance using RMSE and R²
- Residual analysis
- Calculating the Sum of Squared Errors (SSE)
- Comparing actual and predicted sales
- Interpreting results from a business perspective

---

## Future Improvements

Future versions of this project may include:

- Decision Tree Regression
- Random Forest Regression
- Additional business variables such as weather, holidays, and region
- Larger datasets for improved prediction accuracy
- Model comparison between multiple machine learning algorithms