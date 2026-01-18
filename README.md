# Samsung_Project
# Demand Forecasting: ML Model Comparison

This project explores demand forecasting using a dataset containing price, income, and seasonality indices. We compared a simple Linear model against an Ensemble method to determine the best predictor for consumer behavior.

## 📊 Dataset Overview
The dataset includes monthly data points:
- **Price**: The cost of the product.
- **Income**: Average consumer income level.
- **Seasonality_Index**: Seasonal variations.
- **Demand**: The target variable (quantity demanded).

## 🛠️ Data Cleaning & EDA
1. **Duplicate Check**: No duplicate entries were found.
2. **Missing Values**: The dataset was complete with no null values.
3. **Correlation Analysis**: A heatmap was generated to identify feature importance.



## 🤖 Model Comparison
We implemented two different machine learning algorithms to compare performance:

| Model | Mean Squared Error (MSE) | R² Score |
| :--- | :--- | :--- |
| **Linear Regression** | **11.52** | **0.98** |
| Random Forest | 47.18 | 0.94 |

### Key Insight
Linear Regression outperformed Random Forest in this specific case, suggesting a highly linear relationship between the economic features (Price/Income) and the demand.

## 📈 Visualizations
### Actual vs Predicted (Linear Regression)
The comparison plot shows how closely the Linear Regression model matches the ground truth.

