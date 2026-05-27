# Student Performance Analysis

Statistical analysis and predictive modelling of student academic performance using exploratory data analysis, regression modelling, and classification techniques in Python.

## Overview

This project explores how behavioural, demographic, and educational factors relate to student academic performance using real-world student datasets.

The analysis combines exploratory data analysis (EDA), statistical testing, regression modelling, and classification techniques to identify patterns connected to academic outcomes and evaluate the predictive power of different variables.

The project also focuses heavily on interpretation, model evaluation, and discussion of dataset limitations rather than only maximizing predictive accuracy.

## Dataset

The project uses student performance datasets containing demographic, behavioural, social, and educational variables related to academic achievement.

The analysis includes variables such as:

The analysis includes variables such as:

- Study time
- Absences
- Past academic failures
- Parental education
- Family background factors
- Internet access
- Family support
- Student lifestyle and behavioural variables
- Final grades
- Student age and demographic variables

The project compares student performance across both Mathematics and Portuguese subject datasets.

## Analysis Goals

The project investigates several key questions, including:

- Which variables show the strongest relationship with academic performance
- How behavioural and demographic factors influence academic performance
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

## Example Analysis Outputs

The project includes:

- Correlation heatmaps
- Regression model evaluation
- Confusion matrices
- Statistical comparison plots
- Distribution analysis
- Feature relationship visualizations

## Key Findings

Some of the main findings include:

- Past academic failures showed the strongest negative relationship with performance
- Parental education showed a moderate positive relationship
- Study time had a smaller but consistent positive effect
- Most individual variables showed limited predictive power on their own, highlighting the complexity of academic performance prediction
- Increasing model complexity only produced marginal improvements
- Several models showed signs of underfitting and predicted values close to the mean
- Logistic regression classification achieved approximately 70% accuracy

The project emphasizes understanding model behaviour, dataset limitations, and interpretation of statistical relationships rather than only focusing on prediction performance.

## Limitations

Several variables demonstrated relatively weak correlations with academic performance, which limited the predictive performance of some models. The project therefore emphasizes interpretation, model behaviour, and statistical reasoning rather than only maximizing predictive accuracy.

The datasets also contain behavioural and self-reported variables that may not fully capture the complexity of real-world academic performance.

## Technologies Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook
- Statistical modelling
- Machine Learning fundamentals

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter Notebook or VS Code
3. Install the required libraries
4. Run the notebook cells sequentially

Required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Academic Context

This project was developed as part of the UC2SAT102 Statistical Analysis Tools & Techniques course and received a final grade of A.


## Repository Structure
```
student-performance-analysis/
├── assignment/
│   └── student_performance_assignment_specification.pdf
├── data/
│   ├── Prediction_Sample.xlsx
│   ├── Students_Performance_Maths.xlsx
│   ├── Students_Performance_Portuguese.xlsx
│   └── feature_description.txt
├── notebook/
│   └── student_performance_analysis.ipynb
├── report/
│   └── student_performance_analysis_report.pdf
├── README.md
└── .gitignore
```
