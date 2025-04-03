# Student Performance Classification

This project aims to classify student academic performance using four machine learning algorithms: Random Forest Classifier, Extreme Gradient Boost Classifier, Logistic Regression, and Decision Tree Classifier.

## Project Objectives

The primary goal of this project is to build a predictive model that can classify student performance based on historical data. By identifying key factors influencing academic outcomes, educational institutions can take proactive steps to improve student learning results.

## Project Requirements

- **Programming Language**: Python
- **Development Environment**: Jupyter Notebook or any Python IDE

## Required Packages

The following Python packages are used in this project:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical computations
- `matplotlib` and `seaborn`: For data visualization
- `scikit-learn`: For implementing machine learning models and evaluation metrics

## Model Development Process

1. **Data Collection**  
   The dataset used is `xAPI-Edu-Data.csv`, which contains student academic and demographic information.

2. **Exploratory Data Analysis (EDA)**  
   Initial analysis is conducted to understand the data structure, check for missing values, and gain insights using statistics and visualizations.

3. **Data Preprocessing**  
   - **Handling Missing Values**: Detect and manage incomplete data.
   - **Encoding Categorical Variables**: Convert categorical features into numerical values using encoding techniques (e.g., one-hot encoding).
   - **Feature Scaling**: Normalize numerical features to ensure equal contribution during model training.

4. **Train-Test Split**  
   The dataset is split into training and testing sets to evaluate model performance objectively.

5. **Model Training**  
   Four machine learning models are trained:
   - **Logistic Regression**: A statistical model used for binary classification.
   - **Decision Tree Classifier**: A tree-based model for decision making and classification.
   - **Random Forest Classifier**: An ensemble model that uses multiple decision trees to improve accuracy.
   - **Extreme Gradient Boost Classifier (XGBoost)**: A powerful boosting algorithm that combines weak learners to create a strong predictive model.

6. **Model Evaluation**  
   Each model is evaluated using classification metrics such as:
   - Accuracy
   - Precision
   - Recall
   - F1 Score  
