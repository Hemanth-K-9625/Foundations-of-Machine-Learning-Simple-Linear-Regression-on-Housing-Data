# Foundations-of-Machine-Learning-Simple-Linear-Regression-on-Housing-Data
A foundational machine learning project demonstrating the mathematics and implementation of Simple Linear Regression using Scikit-learn for housing price prediction.
🏠 House Price Prediction using Simple Linear Regression
📌 Project Overview

This project demonstrates the implementation of Simple Linear Regression to predict house prices based on a single independent variable (Area).
To strengthen understanding and validate Linear Regression model behavior, the models were trained and evaluated on two different housing datasets.
The objective is to understand:
The mathematical foundation of Linear Regression
Model fitting and interpretation
Performance evaluation using regression metrics

🎯 Problem Statement

Given the area of a house, predict its price using a linear regression model of the form:
𝑃𝑟𝑖𝑐𝑒 = 𝑚 × 𝐴𝑟𝑒𝑎 + 𝑏
Price=m×Area+b
Where:
m → Slope (change in price per unit area)
b → Intercept (base price)
Area → Independent variable
Price → Target variable

📊 Datasets Used
📁 Dataset 1

Contains housing area and corresponding prices
Used to train and evaluate the base model
Helps understand the linear relationship between area and price

📁 Dataset 2
A separate housing dataset with similar structure
Used to validate model consistency and behavior

⚙️ Technologies Used

Python
NumPy
Pandas
Matplotlib
Scikit-learn

🧠 Methodology

Data loading and preprocessing
Exploratory Data Analysis (EDA)
Visualization of area vs price
Model training using Scikit-learn's LinearRegression
Predictions on both datasets
Model evaluation using regression metrics

📈 Model Evaluation Metrics

The following metrics were used to evaluate performance:
-Mean Absolute Error (MAE)
-Mean Squared Error (MSE)
-Root Mean Squared Error (RMSE)
-R² Score
R² Score indicates how well the independent variable explains the variance in house prices.

📊 Visualization

Scatter plot of actual data points
Regression line (best-fit line)
Residual analysis to inspect prediction errors

🚀 Key Learnings

Practical implementation of Linear Regression
Interpretation of slope and intercept
Understanding regression error metrics
Importance of visualization in model interpretation

🔮 Future Improvements

Implement Linear Regression from scratch using Gradient Descent
Extend to Multiple Linear Regression
Add cross-validation
Deploy as a simple web application
Compare performance across datasets using statistical tests

👨‍💻 Author

Hemanth Kumar
Graduate Student – Computer Science
Aspiring Data Scientist / AI Engineer
