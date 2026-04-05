# FUTURE_ML_01
Sales Forecasting using Machine Learning
🚀 Project Overview

This project focuses on building a sales forecasting system using Machine Learning techniques. The goal is to predict future sales based on historical data and provide actionable insights for business decision-making.

Sales forecasting plays a crucial role in:

Inventory planning
Financial management
Demand prediction
Strategic decision-making
🎯 Objective

To develop a regression-based forecasting model that:

Learns from past sales data
Captures time-based patterns
Predicts future demand accurately
🛠️ Tools & Technologies
Python
Jupyter Notebook
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn
📁 Dataset

The dataset contains retail sales data including:

Order Date
Sales
Profit
Quantity
Discount
Region
🔧 Project Workflow
1️⃣ Data Preprocessing
Handled missing values
Converted Order Date to datetime
Cleaned and structured the dataset
2️⃣ Feature Engineering
Extracted time-based features:
Year, Month, Day, DayOfWeek
Created lag features:
lag_1 (previous day sales)
lag_7 (previous week sales)

👉 These lag features enable regression-based forecasting

3️⃣ Model Building
Applied Regression Model (e.g., Linear Regression / Random Forest)
Used time-based train-test split
Trained model on lag features
4️⃣ Model Evaluation
Evaluated using:
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
5️⃣ Visualization
Actual vs Predicted Sales
Sales Trends Over Time
Correlation Heatmap
Discount vs Profit Impact
📊 Key Insights
Sales show time-based patterns and trends
Discounts increase quantity sold but reduce profit margins
Profitability depends on both pricing and sales volume
Historical sales strongly influence future demand
💼 Business Impact

This forecasting system helps businesses:

📦 Optimize inventory management
💰 Improve financial planning
👥 Manage staffing efficiently
📈 Make data-driven decisions