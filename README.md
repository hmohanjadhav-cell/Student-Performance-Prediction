# 🎓 Student Performance Prediction Using Machine Learning

## 📌 Project Overview
The Student Performance Prediction project uses Machine Learning to predict a student's final exam score based on study hours, attendance percentage, and previous scores.

The project uses a Linear Regression model to learn patterns from historical student data and predict expected academic performance.

## 🎯 Objectives
- Predict students' final exam scores.
- Understand the factors affecting student performance.
- Apply Machine Learning techniques to educational data.
- Build an interactive web application using Streamlit.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Google Colab
- GitHub

## 📊 Dataset Description
The dataset contains student information used to train the prediction model.

**Input features:**
- `Hours_Studied` – Hours spent studying per week.
- `Attendance` – Student attendance percentage.
- `Previous_Scores` – Previous academic scores.

**Target variable:**
- `Exam_Score` – Final exam score to be predicted.

The dataset should be provided as a CSV file with these column names.

## ⚙️ Methodology
1. Upload and load the student dataset.
2. Handle missing values and prepare the data.
3. Separate input features and the target variable.
4. Split the dataset into training and testing sets.
5. Train a Linear Regression model.
6. Evaluate the model using Mean Absolute Error (MAE) and R² Score.
7. Predict the final score using user-provided student details.

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install dependencies
```bash
pip install streamlit pandas numpy scikit-learn
```

### 3. Run the Streamlit application
```bash
streamlit run app.py
```

### 4. Upload the dataset
Upload a CSV file containing the required columns and enter the student's details to obtain a predicted score.

## 📈 Model
**Algorithm:** Linear Regression

The model learns the relationship between study hours, attendance, previous scores, and final exam scores.

**Evaluation metrics:**
- Mean Absolute Error (MAE)
- R² Score

Actual evaluation results depend on the dataset used.

## 🌐 Web Application
The application is built using Streamlit and provides an interactive interface for entering student details and viewing predicted exam scores.

Add your deployed website link here if you have a working permanent deployment.

## 🔮 Future Enhancements
- Include more student-related features.
- Compare different Machine Learning algorithms.
- Improve prediction accuracy.
- Deploy the application online for easy access.

## 👨‍💻 Contributors
Add the names and roll numbers of all project team members here.

## 📄 Conclusion
This project demonstrates how Machine Learning can be applied to educational data to estimate student exam performance. It provides a simple interactive tool for exploring the relationship between student study habits, attendance, previous scores, and expected results.
