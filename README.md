# Comparative Analysis of Obesity Dataset

## Introduction

### Project Overview
This project provides a comparative analysis of an obesity dataset to understand the factors contributing to obesity. It involves examining various attributes such as age, gender, physical activities, and dietary habits.

### Objectives
- Explore the distribution and patterns within the obesity dataset.
- Identify key factors contributing to obesity.
- Compare different groups within the dataset (e.g., by gender, age).
- Build predictive models to classify obesity levels based on the given features.
- Provide actionable insights and recommendations based on the analysis.

### Data Sources
The analysis utilizes two datasets:
1. **ObesityDataSet_raw_and_data_sinthetic (1).csv**: Contains raw data with various features related to individuals' physical attributes and lifestyle choices, as well as their obesity levels.
2. **Formatted_dataset.csv**: Processed version of the raw dataset with encoded categorical variables.

## Data Description

### Key Features
- **Age**: Age of the individual.
- **Gender**: Gender of the individual.
- **Height**: Height in meters.
- **Weight**: Weight in kilograms.
- **CALC**: Caloric intake frequency.
- **FAVC**: Frequent consumption of high caloric food.
- **FCVC**: Frequency of vegetable consumption.
- **NCP**: Number of main meals.
- **SCC**: Consumption of food between meals.
- **SMOKE**: Smoking habits.
- **CH2O**: Daily water intake.
- **Family history with overweight**: Family history of being overweight.
- **FAF**: Physical activity frequency.
- **TUE**: Time using technology devices.
- **CAEC**: Consumption of alcohol.
- **MTRANS**: Transportation used.
- **NObeyesdad**: Obesity level.

## Data Preprocessing

### Steps
- Handling missing values: Checked for missing values and imputed/removed as necessary.
- Encoding categorical variables: Converted categorical variables into numeric form.
- Normalizing numerical features: Scaled numerical features to a standard range.
- Splitting the data: Split the dataset into training and testing sets.

## Exploratory Data Analysis (EDA)

### Visualizations
- Distribution of age, height, weight.
- Obesity levels across different age groups and genders.
- Correlation heatmap of features.

### Key Insights
- Distribution and trends observed from the visualizations.
- Correlations between various features.

## Comparative Analysis

### Group Comparisons
- Comparison of obesity levels between males and females.
- Comparison of physical activity levels across different obesity categories.

### Statistical Tests
- Conducted t-tests or ANOVA to identify significant differences between groups.

## Modeling and Results

### Models Used
- **Logistic Regression**: A model that predicts the probability of a binary outcome using input features.
- **Support Vector Machine (SVM)**: A model that finds the hyperplane that best separates the classes in the feature space.

### Performance Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Results
- Comparison of model performance.
- Best performing model and its interpretation.

## Conclusion

### Summary of Findings
- Key factors contributing to obesity identified from the analysis.
- Insights gained from comparing different groups.

### Recommendations
- Suggested interventions based on analysis (e.g., promoting physical activities, dietary changes).

### Future Work
- Further analysis with larger datasets.
- Exploration of additional factors (e.g., genetic predispositions).
- Development of targeted intervention programs.
