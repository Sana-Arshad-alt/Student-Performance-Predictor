# 🎓 Student Performance Predictor

A simple Machine Learning project that predicts whether a student will pass or fail based on study patterns, attendance, and sleep habits.

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 📊 Dataset
A synthetic dataset was created with the following features:
- `study_hours`: Number of study hours per day
- `attendance`: Attendance percentage
- `sleep_hours`: Daily sleep hours
- `passed`: Target variable (1 = Pass, 0 = Fail)

## 🔍 Exploratory Data Analysis
- Pairplot to visualize feature relationships
- Correlation heatmap to find important features

## 🤖 Model Used
- Logistic Regression for binary classification

## 📈 Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

## 📌 Prediction Example
You can predict a new student's result like this:
```python
new_student = pd.DataFrame([[4, 85, 6]], columns=['study_hours', 'attendance', 'sleep_hours'])
model.predict(new_student)
