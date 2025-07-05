# 🏠 Real Estate Housing Price Prediction

A machine learning-driven approach to help real estate investors identify undervalued properties with high return-on-investment (ROI) potential. This project compares two predictive models — Linear Regression and Random Forest — using modified California housing data from the 1990 census.

## 📊 Business Objective

To determine whether machine learning can accurately predict the median house value and guide investors by:
- Highlighting key features that influence housing prices
- Identifying properties listed below market value
- Supporting strategic investment decisions

## 🧠 Models Used

- **Linear Regression**
- **Random Forest Regression**

Performance metrics evaluated:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 🗃️ Dataset

- Modified **California Housing** dataset (1990 census)
- 20,640 records × 10 features
- Includes geographic data, housing details, income, and proximity to the ocean
- Preprocessing steps:
  - Imputed missing `total_bedrooms` with mean
  - Converted categorical `ocean_proximity` into dummy variables
  - Addressed multicollinearity via VIF analysis and column elimination

## 🔬 Key Findings

- Ocean proximity and median income are strong price indicators
- Inland homes offer more stable, lower-risk investments
- Linear Regression slightly outperformed Random Forest across all metrics
- No signs of overfitting: similar performance across training and testing sets

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook / Google Colab
- Git for version control

## 📈 Results Summary

| Model            | R² Score | RMSE     | MAE      |
|------------------|----------|----------|----------|
| Linear Regression| 0.66     | ~68,000  | ~49,000  |
| Random Forest    | 0.65     | ~69,000  | ~49,800  |

## ⚠️ Limitations

- Dataset is from 1990 — significant changes in the real estate market may impact model accuracy
- Inflation and modern market trends are not reflected

## 📌 Business Recommendations

- Use the model to flag homes priced below predicted value
- Cross-validate predictions with recent market data
- Ocean-front properties may offer higher ROI, but also come with volatility
- Continue refining model with updated and diversified datasets

## 🙌 Acknowledgments

Inspired by UC Irvine’s Housing dataset and adapted for educational purposes in our final project.

---

Let me know if you want this in a stylized GitHub-friendly format, like with badges or preview images. I can also help you write usage instructions or set up a `requirements.txt` file if you'd like to package everything professionally.
