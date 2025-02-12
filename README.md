# Building Linear Regression from Scratch

This project walks through the process of building a linear regression model entirely from scratch using Python. No specialized libraries for machine learning or statistics were used in this project—just fundamental mathematical concepts implemented with vanilla libraries like numpy, pandas, and basic plotting libraries to visualize the results.

## Objective
The goal of this project is to provide a deep understanding of how linear regression works by manually implementing every step in the machine learning pipeline. Instead of relying on high-level machine learning libraries like scikit-learn, this project focuses on building the model from the ground up. It uses the US Health Insurance dataset from Kaggle to predict medical insurance costs based on various factors such as age, sex, BMI, location, etc. The decision to use a real-world dataset ensures that the model is practical and relevant, while also demonstrating the application of linear regression to real-world problems. 

## Why Build From Scratch?
The motivation behind this project is to delve deeper into the underlying math and mechanics of linear regression, uncovering the mathematical beauty behind it, and gaining hands-on experience in solving these problems manually. By using basic libraries instead of pre-built functions, this approach enables a clearer understanding of the inner workings, from data preprocessing to model evaluation.

## Key Features of the Project:
1. Fully documented Jupyter Notebook: The notebook is meticulously documented, explaining every step in detail. So, if you are a learner like me, you can refer to this notebook and learn from it easily.
2. Graphical Visualizations: Beautiful, informative plots help explain the data and the model's performance.
3. Hands-on Implementation: Implementing everything from data cleaning, outlier detection, and train-test splitting to the design of the linear regression model, and performance metrics calculations manually.

## Steps Covered in the Project
1. Data Collection
The project uses the US Health Insurance dataset from Kaggle, containing information about individuals and their insurance costs. The goal is to predict medical insurance costs based on individual characteristics like age, sex, BMI, and region.
2. Data Preprocessing
Load and Inspect Data: Load the dataset and perform initial inspection.
Exploratory Data Analysis (EDA): Understand the structure of the data, discover patterns, and identify any issues like missing values or outliers.
Visualize the Data: Various plots (scatter plots, histograms) to visually inspect relationships between features and the target variable.
Handle Skewed Features: Apply appropriate techniques for skewed distributions (e.g., log transformation).
Handle Outliers: Detect and remove outliers based on statistical methods like Z-scores or IQR.
Encode Categorical Features: Convert categorical variables (e.g., sex, region) into numerical formats using one-hot encoding.
Normalize the Data: Scale the data to bring all the features to a similar range.
Split the Data: Divide the dataset into training and testing sets for model validation.
3. Linear Regression Equation: Created the linear regression model mathematically.
4. Gradient Descent
Implement gradient descent from scratch to optimize the model parameters
Gradually update the weights/parameters based on the gradient of the loss function, iterating until convergence.
This helps minimize the MSE and find the optimal values of the parameters.
5. Model Evaluation
The model is evaluated using:
Mean Squared Error (MSE): Measures the average of the squared differences between predicted and actual values.
R-squared (R²): Indicates the proportion of variance in the target variable that is explained by the model.
6. Visualization
Data Points and Fitted Regression Line: Plot the original data points and the regression line that best fits the data.
Convergence of the Cost Function: Visualize how the cost function (MSE) decreases as the gradient descent algorithm converges to the optimal solution.

## Note:
All the requirements, including libraries and dataset used, along with all the graphs are already loaded in the notebook, so refer to the jupyter notebook for them as well.
