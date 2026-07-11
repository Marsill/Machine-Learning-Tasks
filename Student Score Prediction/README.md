Task 1: Student Score Prediction

## Tools

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Task 1

### Objective

Predict students' exam scores using Linear Regression.

### Features Used

- Hours Studied
- Attendance
- Previous Scores
- Tutoring Sessions

### Models Compared

- Linear Regression
- Polynomial Regression

### Results

| Model | MAE | RMSE | R² |
|------|------|------|------|
| Hours Studied | 2.53 | 3.51 | 0.205 |
| Hours + Attendance | 1.53 | 2.65 | 0.548 |
| Hours + Attendance + Previous Scores + Tutoring Sessions | **1.33** | **2.46** | **0.610** |

### Conclusion

The best-performing model was Linear Regression using Hours Studied, Attendance, Previous Scores, and Tutoring Sessions. Polynomial Regression did not improve performance, indicating that the relationship between the selected features and exam score is approximately linear.
