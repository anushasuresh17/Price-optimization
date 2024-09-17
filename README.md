# Price-optimization

This project focuses on optimizing product prices using machine learning models, specifically Random Forest, in combination with price elasticity simulation. The dataset includes various product features, sales data, and profitability information. The goal is to find an optimal price point that maximizes profit while considering factors such as quantity, discounts, and product categories.

Project Structure
1. Data Preprocessing
Cleaned the dataset and created new features such as unit price, profit margin, and discount rate.
Extracted date-related features from the order date (year, month, weekday).
One-hot encoded categorical variables such as product category and sub-category.
2. Exploratory Data Analysis
Performed correlation analysis to understand relationships between numerical features.
Visualized key relationships such as the impact of discounts on profit and the distribution of unit prices across product categories.
3. Modeling
Trained and evaluated several models including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest.
Random Forest emerged as the best model with the lowest RMSE (80.79) and the highest R² (0.408), making it the ideal model for predicting optimized prices.
4. Price Optimization
Simulated different discount rates to assess their impact on profit using price elasticity.
Used the Random Forest model to predict optimized prices based on factors like quantity, discount, profit margin, and product features.
Compared the predicted optimized prices to the current prices to determine more profitable price points.
5. Results
The Random Forest model proved effective in suggesting price adjustments that increased overall profitability. Simulated profits improved for many products, confirming the model’s strength in identifying optimal price points.
6. Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
Machine Learning Models: Random Forest, Linear Regression, Ridge, Lasso
Price elasticity simulations
7. Conclusions
Random Forest is better suited for price optimization due to its ability to capture complex, nonlinear relationships between variables.
Pricing strategies need to balance profitability and sustainability, which can be achieved through machine learning.
