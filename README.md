# Student Dropout Prediction System

A college mini-project that predicts the likelihood of student dropout using Machine Learning (Logistic Regression). No backend server is required! The entire system runs offline in the browser.

## Features
- **Offline ML Model:** The weights and logic are embedded directly in the JavaScript.
- **Predictive Factors:** Uses Attendance %, GPA, Family Income, Study Hours, and Previous Exam Score to calculate risk.
- **Detailed Insights:** Provides a dynamic risk meter, feature-wise risk analysis, and actionable recommendations.

## Live Demo
This project is configured to automatically deploy to GitHub Pages via GitHub Actions.

Live URL: https://renukaramesh2327.github.io/student-drop-prediction/

## Project Structure
- `index.html`: The main web interface containing the CSS, UI components, and ML logic.
- `data/student_data.csv`: A sample dataset representing synthetic student records.

## How It Works
The system uses a Logistic Regression model trained on 500 synthetic student records. It normalizes inputs (z-score scaling) and applies pre-computed feature weights via a Sigmoid function to derive a probability score.
