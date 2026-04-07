📊 Height vs Weight Prediction using Linear Regression
📌 Overview

This project demonstrates how to use Linear Regression to predict a person’s weight based on their height. It is a simple and beginner-friendly example to understand how machine learning models identify relationships between variables.

📁 Dataset Description

The dataset contains information about individuals' Height and their corresponding Weight.

🔑 Features:
Height → Independent variable (input)
Weight → Dependent variable (output)
📄 Sample Data:
Height (cm)	Weight (kg)
150	50
155	55
160	60
165	65
170	70
🎯 Objective

The main goal of this project is to:

Understand the relationship between height and weight
Build a linear regression model
Predict weight for a given height
Visualize the data and regression line
🧠 Concept Used

The model is based on the linear equation:

𝑦
=
𝑚
𝑥
+
𝑏
y=mx+b
𝑚
m
𝑏
b
-10
-8
-6
-4
-2
2
4
6
8
10
-10
-5
5
10
y-intercept
x-intercept

Where:

y = Predicted Weight
x = Height
m = Slope (how weight changes with height)
b = Intercept (base weight value)
⚙️ Steps Involved
Load Dataset
Preprocess Data
Check for missing values
Split Data
Training set
Testing set
Train Model
Apply Linear Regression
Make Predictions
Evaluate Model
Mean Squared Error (MSE)
R² Score
Visualize Results
Scatter plot of data
Regression line
📈 Expected Outcome
A straight line representing the relationship between height and weight
Ability to estimate a person’s weight using their height
🛠️ Requirements
Python 3.x
(Optional libraries):
NumPy
Pandas
Matplotlib
Scikit-learn
🚀 How to Run
Download or clone the project
Place the dataset file (e.g., height_weight.csv) in the project folder
Run the script:
python linear_regression.py
📊 Use Cases
Health and fitness analysis
BMI estimation (with additional data)
Educational demonstrations of regression
📌 Conclusion

This project helps beginners understand how Linear Regression can be applied to real-world data to predict continuous values like weight based on height.
