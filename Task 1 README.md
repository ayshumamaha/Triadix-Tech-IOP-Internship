# AI-Powered Student Performance Prediction System

## Overview

The **AI-Powered Student Performance Prediction System** is a Machine Learning project developed using Python to analyze student performance data and predict academic outcomes based on various educational and personal factors. The project performs data preprocessing, exploratory data analysis (EDA), trains multiple machine learning models, compares their performance, identifies the most influential features, and predicts the performance category of new student records.

---

## Objectives

* Analyze student performance data.
* Perform data cleaning and preprocessing.
* Explore relationships between different student attributes.
* Train multiple machine learning classification models.
* Compare model performance using accuracy.
* Predict the performance category of new student records.
* Identify the most influential factors affecting academic success.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Project Structure

```text
AI-Student-Performance-Prediction/
│
├── student_performance.csv
├── Student_Performance_Prediction.py
├── best_model.pkl
├── correlation_heatmap.png
├── score_distribution.png
├── attendance_vs_score.png
├── studytime_vs_score.png
├── model_accuracy.png
├── feature_importance.png
└── README.md
```

---

## Dataset

The project uses a student performance dataset containing the following attributes:

* Gender
* Age
* StudyTime
* Attendance
* PreviousGrade
* Internet
* ParentEducation
* ExtraClasses
* SleepHours
* AssignmentsCompleted
* FinalScore
* Performance (Target Variable)

---

## Features

* Data loading from CSV file
* Duplicate record removal
* Missing value handling
* Label encoding of categorical variables
* Exploratory Data Analysis (EDA)
* Correlation heatmap generation
* Distribution and scatter plot visualization
* Train-test dataset splitting
* Logistic Regression model
* Decision Tree model
* Random Forest model
* Gradient Boosting model
* Model accuracy comparison
* Feature importance analysis
* Student performance prediction
* Model saving using Joblib

---

## Machine Learning Algorithms

The following supervised learning algorithms are implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting

The best-performing model is automatically selected based on prediction accuracy.

---

## Output Files

The project generates the following output files after successful execution:

* correlation_heatmap.png
* score_distribution.png
* attendance_vs_score.png
* studytime_vs_score.png
* model_accuracy.png
* feature_importance.png
* best_model.pkl

---

## How to Run

1. Install the required Python libraries.
2. Place `student_performance.csv` in the project folder.
3. Open `Student_Performance_Prediction.py` in Google Colab or any Python IDE.
4. Execute the program.
5. View the generated graphs, prediction results, and saved model.

---

## Expected Results

After execution, the project will:

* Display dataset information.
* Clean and preprocess the dataset.
* Generate exploratory data analysis graphs.
* Train four machine learning models.
* Compare model accuracies.
* Identify the best-performing model.
* Display feature importance.
* Predict the academic performance of a new student.
* Save the trained model for future use.

---

## Future Enhancements

* Develop a web application using Flask or Django.
* Integrate real-time database connectivity.
* Implement deep learning models.
* Deploy the model as a cloud-based service.
* Add interactive dashboards for educational institutions.
* Improve prediction accuracy using larger datasets.

---

## Author

**M. Ayshwarya**
Aeronautical Engineering Graduate
