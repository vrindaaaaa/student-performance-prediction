# Student Performance Prediction App

A machine learning-powered web application to analyze and predict student performance based on academic, behavioral, and socio-demographic factors. This project helps educators identify students at risk and take timely interventions.

---

## Project Overview

Student performance is affected by many factors beyond academics, such as attendance, study habits, and access to resources. This app combines machine learning with an interactive Streamlit interface to:

- Predict if a student will pass or fail
- Estimate the exam score
- Provide interactive data visualizations
- Help in early identification of at-risk students

---

## Features

- Data Visualization (heatmaps, bar charts, pie charts, etc.)
- ML-based Predictions (classification and regression)
- User Input Panel for Real-time Results
- Model Accuracy Displayed
- Visual Feedback with GIFs for Pass/Fail

---

## Technologies Used

- Frontend/UI: Streamlit  
- ML/Backend: Python, scikit-learn, pandas, numpy  
- Visualization: seaborn, matplotlib  
- Datasets:
  - UCI Student Performance Dataset: https://archive.ics.uci.edu/ml/datasets/Student+Performance
  - Kaggle - Student Performance Dataset: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

---

## Machine Learning Models Used

- Random Forest Classifier → For predicting Pass/Fail  
- Random Forest Regressor → For predicting Exam Score

---

## Project Structure

```
├── CODE.docx                      # Streamlit app source code
├── StudentPerformanceFactors.csv  # Dataset used
├── style.css                      # Optional custom CSS styling
├── image_home.jpeg                # Welcome page image
├── pass.gif                       # Shown when student passes
├── fail.gif                       # Shown when student fails
├── README.md                      # Project documentation (this file)
```

---

## How to Run Locally

1. Clone the Repository
```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```

2. Install Required Packages
```bash
pip install -r requirements.txt
```

To create `requirements.txt`:
```bash
pip freeze > requirements.txt
```

3. Run the App
```bash
streamlit run your_app_file.py
```

---

## Input Fields for Prediction

- Attendance (%)
- Hours Studied per Week
- Previous Scores (out of 100)
- Access to Resources (Low / Medium / High)
- Tutoring Sessions per Week

---

## Model Performance

- Classification Accuracy: ~87%  
- Regression RMSE: ~1.75

---

## Authors

- Reeshal Dsouza (4CB23AI079)  
- Sanjana Mahale (4CB23AI087)  
- Vrinda Bhaskar Kumtakar (4CB23AI125)  

Guide: Mr. Arjun K  
Department of Artificial Intelligence & Machine Learning  
Canara Engineering College, VTU Belagavi


---

