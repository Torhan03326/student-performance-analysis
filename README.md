# Student Performance Analysis

Statistical analysis and predictive modelling of student academic performance using exploratory data analysis, regression modelling, and classification techniques in Python.

## Overview

This project explores how behavioural, demographic, and educational factors relate to student academic performance using real-world student datasets.

The analysis combines exploratory data analysis (EDA), statistical testing, regression modelling, and classification techniques to identify patterns connected to academic outcomes and evaluate the predictive power of different variables.

The project also focuses heavily on interpretation, model evaluation, and discussion of dataset limitations rather than only maximizing predictive accuracy.

## Dataset

The project uses student performance datasets containing demographic, behavioural, social, and educational variables related to academic achievement.

The analysis includes variables such as:

- Study time
- Absences
- Past academic failures
- Parental education
- Alcohol consumption
- Internet access
- Romantic relationships
- Family support
- Final grades
- Student age and lifestyle-related variables

The project compares student performance across both Mathematics and Portuguese subject datasets.

## Analysis Goals

The project investigates several key questions, including:

- Which variables show the strongest relationship with academic performance
- How behavioural and demographic variables influence grades
- Whether student performance can be predicted using regression models
- How classification models perform on academic outcome prediction
- Whether increased model complexity improves predictive performance
- How different student groups compare statistically
- How model limitations affect interpretation of results

## Techniques Used

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature engineering
- Multiple Linear Regression
- Logistic Regression
- Classification analysis
- Statistical significance testing
- Independent t-tests
- Confusion matrix analysis
- Precision, Recall, and F1-score evaluation
- Model evaluation and interpretation
- Underfitting analysis
- Data visualization

## Key Findings

Some of the main findings include:

- Past academic failures showed the strongest negative relationship with performance
- Parental education showed a moderate positive relationship
- Study time had a smaller but consistent positive effect
- Most variables demonstrated relatively weak predictive power individually
- Increasing model complexity only produced marginal improvements
- Several models showed signs of underfitting and predicted values close to the mean
- Logistic regression classification achieved approximately 70% accuracy

The project emphasizes understanding model behaviour, dataset limitations, and interpretation of statistical relationships rather than only focusing on prediction performance.

## Technologies Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Academic Context

This project was developed as part of the UC2SAT102 Statistical Analysis Tools & Techniques course and received a final grade of A.

## Repository Structure

```text
student-performance-analysis/
├── assignment/
│   └── student_performance_assignment_specification.pdf
├── data/
│   └── student-mat.csv
│   └── student-por.csv
├── notebook/
│   └── student_performance_analysis.ipynb
├── report/
│   └── student_performance_analysis_report.pdf
├── README.md
└── .gitignore
```
