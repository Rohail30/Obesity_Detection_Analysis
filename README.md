# Obesity Dataset Analysis

## Overview

This project aims to analyze a dataset related to obesity levels using various machine learning models. The dataset contains information about individuals' demographics, lifestyle habits, and family history related to obesity. The objective is to predict the obesity level of individuals based on these features.

## Dataset Description

The dataset consists of 2,111 entries and 17 columns. Here is an overview of each column:

- **Gender**: Gender of the individual
- **Age**: Age of the individual
- **Height**: Height of the individual
- **Weight**: Weight of the individual
- **family_history_with_overweight**: Indicates if a family member suffers from overweight
- **FAVC**: Indicates if the individual frequently eats high-caloric food
- **FCVC**: Indicates if the individual usually eats vegetables in their meals
- **NCP**: Number of main meals the individual has daily
- **CAEC**: Indicates if the individual eats food between meals
- **SMOKE**: Indicates if the individual smokes
- **CH2O**: Amount of water the individual drinks daily
- **SCC**: Indicates if the individual monitors their daily calorie intake
- **FAF**: Frequency of physical activity
- **TUE**: Time spent using technological devices
- **CALC**: Frequency of alcohol consumption
- **MTRANS**: Mode of transportation usually used by the individual
- **NObeyesdad**: Obesity level (Target Variable)

## Project Structure

The analysis was conducted using four different machine learning models to predict obesity levels:

1. **K-Nearest Neighbors (KNN) Classifier**
2. **Decision Tree Classifier**
3. **Logistic Regression**
4. **Random Forest Classifier**

### K-Nearest Neighbors (KNN) Classifier

- **Preprocessing**: Features were standardized to ensure they have a mean of 0 and a standard deviation of 1.
- **Train-Test Split**: The dataset was split into 70% training and 30% testing sets.
- **Accuracy**: The KNN classifier achieved an accuracy of 84.70%.

### Decision Tree Classifier

- **Train-Test Split**: The dataset was split into 60% training and 40% testing sets.
- **Accuracy**: The Decision Tree classifier achieved an accuracy of 92.43%.

### Logistic Regression

- **Preprocessing**: Features were standardized similar to the KNN model.
- **Train-Test Split**: The dataset was split into 50% training and 50% testing sets.
- **Accuracy**: The Logistic Regression model achieved an accuracy of 86.27%.

### Random Forest Classifier

- **Train-Test Split**: The dataset was split into 60% training and 40% testing sets.
- **Accuracy**: The Random Forest classifier achieved the highest accuracy of 95.62%.

## Conclusion

This project demonstrates the application of different machine learning models to predict obesity levels based on a variety of features. The Random Forest classifier performed the best among the models tested, with an accuracy of 95.62%. This analysis provides insights into the factors influencing obesity and showcases the effectiveness of various classification algorithms in predicting obesity levels.

## How to Use

1. **Clone the Repository**: Clone the repository to your local machine using `git clone <repository-url>`.
2. **Install Dependencies**: Install the necessary Python libraries using `pip install -r requirements.txt`.
3. **Run the Analysis**: Execute the provided Jupyter notebooks or Python scripts to reproduce the analysis and predictions.

## Future Work

- **Hyperparameter Tuning**: Further improve model performance by tuning hyperparameters.
- **Feature Engineering**: Explore additional feature engineering techniques to enhance model accuracy.
- **Model Comparison**: Evaluate other machine learning models and ensemble methods to potentially achieve better results.



