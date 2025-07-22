 Student Performance Predictor

This is a simple machine learning project that predicts whether a student will **pass or fail** based on their **math** and **reading** scores.

---

 What this project does

- Takes two scores from a student:  
  ➤ Math Score  
  ➤ Reading Score

- Predicts whether the student will pass (1) or fail (0)

---

Dataset Used

I used a dataset called **Students Performance**, which contains information about students and their exam scores.  
📁 Link to dataset: [Click here](https://raw.githubusercontent.com/YBI-Foundation/Dataset/main/Students%20Performance.csv)

---

 Tools I Used

- **Python**
- **Pandas** – to handle the data  
- **Scikit-learn** – to build the ML model  
- **Google Colab** – to run the code online

---

 Steps I Followed

1. Collected the data
2. Picked only the math and reading scores
3. Created a new column that says "Pass" if score is good
4. Trained a simple machine learning model (Logistic Regression)
5. Tested it to see how accurate it is
6. Made predictions for new students

---

 Sample Prediction

```python
model.predict([[55, 70]])  # Output: 1 → This student will pass
