
 Student Performance Predictor

This project predicts whether a student will pass or fail using their math and reading scores. It uses **Logistic Regression**, a basic machine learning model.
Project Objective
To build a simple ML model that:
- Takes input: `math score`, `reading score`
- Predicts: `Pass` (1) or `Fail` (0)
- Achieves good accuracy with minimal features

 Dataset
[Students Performance Dataset](https://raw.githubusercontent.com/YBI-Foundation/Dataset/main/Students%20Performance.csv)

 Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab

 Steps Performed
1. Loaded dataset
2. Cleaned & selected features
3. Added a binary 'Pass' label
4. Trained Logistic Regression model
5. Evaluated accuracy
6. Predicted outcomes for new students

 Sample Prediction
```python
new_student = [[55, 70]]
model.predict(new_student)  # Output: 1 → Pass
