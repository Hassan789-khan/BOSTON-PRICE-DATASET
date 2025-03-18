# BOSTON-PRICE-DATASET
Objective
The goal of this project is to build a regression model from scratch to predict house prices using the Boston Housing Dataset. Three different models—Linear Regression, Random Forest, and XGBoost—were implemented and evaluated to compare their performance.

1️⃣ Data Preprocessing
Dataset Cleaning: Removed unnecessary columns (CHAS, ZN) and handled missing values.
Feature Engineering: Standardized numerical features for better model performance.
Outlier Handling: Detected and removed outliers to improve prediction accuracy.
2️⃣ Model Implementation (From Scratch)
✅ Linear Regression: Implemented using gradient descent without using built-in libraries.
✅ Random Forest: Built a custom decision tree-based model for ensemble learning.
✅ XGBoost: Created an optimized boosting algorithm for better prediction accuracy.

3️⃣ Performance Evaluation
Models were compared using Root Mean Squared Error (RMSE) and R² Score.
Performance metrics were calculated to determine the best regression model.
4️⃣ Feature Importance Visualization
For tree-based models (Random Forest & XGBoost), feature importance was plotted to understand which features impact house prices the most.
The visualization helps in interpreting the model results and understanding key predictors.
Results & Conclusion
XGBoost performed the best in terms of accuracy and error minimization.
Feature importance analysis showed that factors like crime rate, average number of rooms, and property tax rates significantly influenced house prices.
This project successfully demonstrated the implementation of regression models without using pre-built libraries, making it a strong learning experience in machine learning fundamentals.
