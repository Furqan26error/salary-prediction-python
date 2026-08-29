# Employee Salary Prediction

## About the Project

This project uses Python and Machine Learning to predict
employee salary based on years of experience.

The project follows a basic machine learning workflow,
including data exploration, data cleaning, visualization,
model training, prediction, and evaluation.

## Dataset

The dataset contains information about:

- Age
- Experience
- Hours
- Salary

The dataset contains 20 employee records.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Steps

### 1. Data Exploration

The dataset was examined by checking its shape, column
names, and data types.

### 2. Data Cleaning

Missing values were identified and replaced using the
median value of the corresponding column.

Outliers were also examined using boxplots and extreme
values were removed using defined thresholds.

### 3. Data Visualization

Visualizations were created to understand the relationship
between employee experience and salary.

### 4. Machine Learning

Linear Regression was used to predict salary based on
years of experience.

The data was divided into training and testing sets using
an 80/20 split.

### 5. Model Evaluation

The model was evaluated using Mean Absolute Error (MAE).

The resulting MAE was approximately 2052.

### 6. New Prediction

The trained model was used to predict the salary of a new
employee with 10 years of experience.

The predicted salary was approximately 54741.

## Files

- `employee_salary_prediction.ipynb` - Jupyter Notebook containing the complete analysis and machine learning workflow.
- `employee_salary.csv` - Employee dataset.
- `requirements.txt` - Python libraries required for the project.

## Conclusion

This project demonstrates a basic machine learning workflow
for predicting employee salary using Linear Regression and
employee experience as the main feature.