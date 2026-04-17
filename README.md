# Student Absenteeism Prediction

## 📌 Project Overview
A Machine Learning project focused on analyzing and predicting student absences based on demographic and academic data.

## 🚀 Key Features
* *Exploratory Data Analysis:* Heatmaps and Histograms to understand data patterns.
* *Data Preprocessing:* Encoding categorical variables for ML readiness.
* *Modeling:* Linear Regression model to forecast absences.
* *Evaluation:* Achieved an RMSE of 7.45.

## 📈 Key Results & Visualizations

In this section, we showcase how the *Multiple Linear Regression* model performs visually.

### 1. Actual vs. Predicted Absences
This scatter plot compares the real values from the test set against our model's predictions. The alignment along the diagonal indicates the model's accuracy.

### 2. Regression Analysis: Study Time
We visualized the linear relationship between Study Time and Absences to see how academic habits impact attendance.

**Note:** You can find the full evaluation code and interactive plots in the [Jupyter Notebook](./student_absence_multiple_linear_regression.ipynb).


## 🛠️ Tech Stack
* Python (Pandas, Scikit-Learn, Seaborn)
* Google Colab

​🔮 Future Work
​To improve the model's accuracy and depth, the following steps can be taken:
​Try Different Models: Implementing more complex algorithms like Random Forest Regressor or XGBoost to capture non-linear relationships.
​Feature Engineering: Creating new features, such as "Total Grade Average" or "Study-to-Free-Time Ratio," to see if they impact absenteeism more than individual variables.
​Cross-Validation: Using K-Fold Cross-Validation to ensure the model's performance is consistent across different subsets of the data.
​Hyperparameter Tuning: Using GridSearchCV to find the optimal settings for the models and reduce the RMSE even further.
​Deployment: Building a simple web interface using Streamlit where teachers can input student data and get an immediate absenteeism risk prediction.

​👤 Author

​Hala Alkhawaldeh _ Data Science & AI Student
