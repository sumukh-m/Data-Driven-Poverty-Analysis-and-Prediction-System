
# Data Driven Poverty Analysis and Prediction System
Project focuses on utilizing data-driven techniques to analyze and predict poverty probabilities in various countries. By using metrics such as literacy rates and income levels, we aim to provide valuable insights into poverty trends and potential outcomes. Through a systematic approach to data analysis, we seek to contribute to a deeper understanding of poverty dynamics and inform targeted interventions for improvement.

Accuracy
<pre>
            Linear Regression  KNN      Random Forest     SVM
Python            72%          68%          70%           69%
R                 72%          72%          75%           74%

</pre>


# Implementation Overview

Exploratory Data Analysis (EDA):
We start by understanding the dataset's characteristics, distributions, and potential patterns. EDA helps us gain insights that guide our subsequent steps.

![image](https://github.com/sumukh-m/Data-Driven-Poverty-Analysis-and-Prediction-System/blob/master/Screenshots/eda1.png)

Data Cleaning and Preprocessing:

Handling Missing and Infinite Values: We address missing and infinite values in the dataset to ensure data integrity.

Dataset Splitting: The data is divided into training and testing subsets, crucial for model evaluation.

Label Encoding: Categorical data is encoded to numeric format for model compatibility.
Feature Selection: We identify the most relevant features that contribute to predicting poverty probabilities.

Model Training and Evaluation:

Linear Regression: This basic regression technique helps us establish a baseline for predictive performance.

K-Nearest Neighbors (KNN): By finding similar instances, KNN aids in understanding the neighborhood of poverty probabilities.

Random Forest: This ensemble method leverages decision trees to capture complex relationships within the data.

Support Vector Machine (SVM): SVM finds hyperplanes that optimally separate different poverty probability categories.

Each model is trained on the training subset and evaluated using the testing subset, using appropriate metrics to gauge their predictive accuracy.

Results and Evaluation

# Python Results
![image](https://github.com/sumukh-m/Data-Driven-Poverty-Analysis-and-Prediction-System/blob/master/Screenshots/Python.PNG)

# R Results
![image](https://github.com/sumukh-m/Data-Driven-Poverty-Analysis-and-Prediction-System/blob/master/Screenshots/R.PNG)


