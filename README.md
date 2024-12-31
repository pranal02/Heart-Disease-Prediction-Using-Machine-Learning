# Heart-Disease-Prediction-Using-Machine-Learning
# Project Overview
- This project aims to build and evaluate machine learning models to predict the risk of heart disease in patients based on various health metrics. Using the UCI Heart Disease Dataset, we implement and compare three classification models: Logistic Regression, Decision Tree, and Random Forest. The project includes data analysis, visualization, model building, evaluation, and selection of the best model based on performance metrics.

# Dataset
- Source: UCI Heart Disease Dataset
- Description: The dataset contains 14 attributes, with the target attribute indicating the presence or absence of heart disease. The features include age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, resting ECG results, maximum heart rate achieved, exercise-induced angina, and more.

# Installation
- Clone the repository to your local machine:
git clone https://github.com/pranal02/Heart-Disease-Prediction-Using-Machine-Learning.git
- Navigate to the project directory :
cd Heart-Disease-Prediction-Using-Machine-Learning
- Create and activate a virtual environment :
  python -m venv venv
  
  source venv/bin/activate

# Tasks Performed
# 1. Data Analysis
- Import Dataset: Load the dataset into a pandas DataFrame and inspect the first few rows.
- Descriptive Statistics: Calculate mean, median, quartiles, and other statistics for each attribute.
- Data Cleaning: Check for missing values, outliers, and data types, and perform necessary data cleaning steps.
- Correlation Analysis: Identify the correlation between features using a correlation matrix.
# 2. Data Visualization
- Distribution of Target Variable: Visualize the count of patients with and without heart disease.
- Age Distribution vs. Target: Plot the distribution of age for patients with and without heart disease.
- Correlation Heatmap: Visualize the correlation between all features using a heatmap.
- Additional Visualizations:
- 
Distribution of cholesterol levels.
Maximum heart rate achieved vs. heart disease presence.
Box plots of various features against the target variable.
# 3. Logistic Regression
- Data Splitting: Split the dataset into training (70%) and testing (30%) sets.
- Model Building: Build and train a Logistic Regression model on the training set.
- Prediction and Evaluation:
- Predict the target values for the test set.
- Calculate the accuracy score and build a confusion matrix.
- Generate a classification report with precision, recall, and F1-score.
# 4. Decision Tree
- Model Building: Build and train a Decision Tree classifier.
- Prediction and Evaluation:
- Predict the target values for the test set.
- Calculate the accuracy score and build a confusion matrix.
- Visualize the Decision Tree using the Graphviz package.
# 5. Random Forest
- Model Building: Build and train a Random Forest classifier.
- Prediction and Evaluation:
- Predict the target values for the test set.
- Calculate the accuracy score and build a confusion matrix.
- Visualize the feature importance and the model using the Graphviz package.
# 6. Model Comparison and Evaluation
- Confusion Matrices: Display confusion matrices for all classifiers.
- Classification Reports: Print precision, recall, F1-score, and support for each classifier.
- Model Selection: Choose the best model based on accuracy, precision, recall, and F1-score.
- Confusion Matrix Heatmaps: Visualize confusion matrices using heatmaps for all models.
# Results
- Logistic Regression: Achieved an accuracy of 81.31%.
- Decision Tree: Achieved an accuracy of 73.62%.
- Random Forest: Achieved an accuracy of 82.41%.
- The Random Forest model performed the best with the highest accuracy and balanced precision, recall, and F1-score.

# Conclusion
- In this project, we built and evaluated three machine learning models to predict the risk of heart disease in patients. The Random Forest classifier was selected as the best model based on its performance metrics. The visualizations and model evaluations provided valuable insights into the factors contributing to heart disease risk.
