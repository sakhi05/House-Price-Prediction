# 🏠 Real Estate Housing Price Prediction

A data-driven machine learning project designed to empower real estate investors with actionable insights. By analyzing the California Housing dataset (1990 census), this project predicts median house values and identifies undervalued properties with high ROI potential. The workflow demonstrates how predictive analytics can guide strategic investment decisions in dynamic real estate markets.

## 📊 Business Objective

- Accurately estimate median house values using advanced regression models
- Highlight the most influential features affecting property prices
- Identify properties priced below market value for investment opportunities
- Support data-driven decision-making for real estate professionals

## 🧠 Models Used

- **Linear Regression**
- **Random Forest Regression**

Performance evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 🗃️ Dataset

- Modified **California Housing** dataset (1990 census)
- 20,640 records × 10 features
- Features: geographic data, housing characteristics, income, ocean proximity
- Preprocessing included:
  - Imputation of missing values
  - Categorical encoding (`ocean_proximity`)
  - Multicollinearity reduction (VIF analysis)

## 🔬 Key Insights

- **Median income** and **ocean proximity** are the strongest predictors of price
- Inland homes offer more stable, lower-risk investments
- Linear Regression and Random Forest achieved similar performance (R² ≈ 0.65)
- No overfitting observed; robust generalization across data splits

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib / Seaborn (visualization)
- Jupyter Notebook / Google Colab
- Git for version control

## 📈 Results Summary

| Model            | R² Score | RMSE     | MAE      |
|------------------|----------|----------|----------|
| Linear Regression| 0.66     | ~68,000  | ~49,000  |
| Random Forest    | 0.65     | ~69,000  | ~49,800  |

## ⚠️ Limitations

- Dataset reflects 1990 market conditions; not adjusted for inflation or recent trends
- Model performance may vary with current data

## 📌 Business Recommendations

- Use the model to flag homes priced below predicted value for investment
- Prioritize median income and ocean proximity in property evaluations
- Validate predictions with up-to-date market data
- Continuously retrain models with new datasets for improved accuracy

## 🙌 Acknowledgments

Inspired by UC Irvine’s Housing dataset and developed as a capstone project for advanced data science coursework.

---

*For more details, see the Jupyter notebook in this repository.*