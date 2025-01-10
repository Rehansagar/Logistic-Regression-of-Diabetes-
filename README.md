# Logistic-Regression-Project Implementation 
Implementation of Logistic Regression on Diabetes Data.

Let’s explore logistic regression and its implementation step-by-step to predict whether a patient is Diabetic or Non-Diabetic.

What is Logistic Regression?
Logistic Regression is a classification algorithm used for binary outcomes like True/False or Yes/No. Here, we use it to predict diabetes status.
It relies on the Sigmoid Function:
σ(x) =1 /  1 + e^−x
This maps predictions to probabilities between 0 and 1. A threshold of 0.5 determines the class (1 = Diabetic, 0 = Non-Diabetic).
Steps in the Project:
1. Dataset Overview:
768 rows, 8 features (health metrics like glucose level, BMI, etc.).

2. Exploratory Data Analysis (EDA):
Used shape, corr(), and describe() to understand the data.
Plotted a Correlation Heatmap to identify relationships between features.

3. Data Cleaning and Imputation:
Replaced zeros in symmetric features with the mean and in non-symmetric features with the median (more robust to outliers).

4. Outlier Handling:
Applied the IQR method to detect and address outliers.

5. Feature Scaling:
Standardized data to a range of -1 to +1 using Standard Scaler.

6. Train-Test Split:
Split the data into training and testing sets.

7. Handling Imbalanced Data:
Used SMOTE to balance the dataset since there were twice as many Non-Diabetic cases (0) as Diabetic cases (1).

8. Model Training:
Trained a Logistic Regression model using sklearn.

9. Evaluation:
Achieved an accuracy of 74%, indicating room for improvement.
There is much more other than this want more clear explanation feel free to DM.
I learned this under the guidance of Priya Bhatia Ma'am.

You can checkout on Google Colab 1.https://https://lnkd.in/duxeNi-D
2. https://lnkd.in/dD_h_kTJ
