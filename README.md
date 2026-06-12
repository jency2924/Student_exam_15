# Student Exam Pass Prediction System

## Project Overview

The Student Exam Pass Prediction System is a Machine Learning project that predicts whether a student is likely to **Pass** or **Fail** in the final examination based on academic and demographic factors. The project uses **Logistic Regression** for prediction and provides insights through **Exploratory Data Analysis (EDA)** and interactive visualizations.

The system helps educational institutions identify students who are at risk of failing and enables timely academic interventions to improve student performance.

---

## Problem Statement

Educational institutions collect large amounts of student performance data such as study hours, attendance rates, previous exam scores, parental education levels, and extracurricular activities. Manually analyzing this data to identify at-risk students is difficult and time-consuming.

This project automates the analysis process and predicts student pass/fail outcomes using machine learning techniques.

---

## Objectives

* Analyze student academic performance data.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Identify factors influencing student success.
* Build a Logistic Regression prediction model.
* Evaluate model performance using classification metrics.
* Categorize students based on risk levels.
* Create an interactive dashboard for visualization.

---

## Dataset Information

### Dataset Source

Kaggle

### Dataset Name

Student Performance Prediction Dataset

### Features Used

| Column Name                | Description                 |
| -------------------------- | --------------------------- |
| Student_ID                 | Unique Student Identifier   |
| Gender                     | Male/Female                 |
| Study_Hours_per_Week       | Weekly study hours          |
| Attendance_Rate            | Attendance percentage       |
| Past_Exam_Scores           | Average previous exam score |
| Parental_Education_Level   | Parent education level      |
| Internet_Access_at_Home    | Internet availability       |
| Extracurricular_Activities | Participation in activities |
| Final_Exam_Score           | Final examination score     |
| Pass_Fail                  | Target Variable             |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Streamlit

---

## Project Workflow

### 1. Data Collection

* Load dataset from CSV file.
* Understand dataset structure.
* Identify numerical and categorical variables.

### 2. Data Preprocessing

* Handle missing values.
* Remove duplicate records.
* Encode categorical variables.
* Drop unnecessary columns.
* Scale numerical features.

### 3. Exploratory Data Analysis (EDA)

* Study student performance patterns.
* Analyze attendance and study habits.
* Compare pass and fail students.
* Evaluate academic factors.

### 4. Visualization

* Bar Charts
* Histograms
* Scatter Plots
* Box Plots
* Correlation Heatmaps

### 5. Risk Analysis

Students are classified into:

#### High Risk

* Low attendance
* Low study hours
* Poor previous scores

#### Medium Risk

* Average attendance and performance

#### Low Risk

* High attendance
* High study hours
* Strong academic history

### 6. Machine Learning Model

Algorithm Used:

**Logistic Regression**

Steps:

* Feature Selection
* Train-Test Split
* Model Training
* Prediction
* Probability Estimation

### 7. Model Evaluation

Metrics Used:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

### 8. Dashboard Development

Dashboard Features:

* Pass vs Fail Distribution
* Attendance Analysis
* Study Hours Analysis
* Gender-wise Performance
* Internet Access Impact
* Correlation Heatmap
* Risk Category Analysis





---

## Expected Output

The system predicts whether a student is likely to Pass or Fail and provides visual insights into factors affecting academic success.

Benefits include:

* Early identification of at-risk students
* Better academic planning
* Improved student performance
* Data-driven decision making
* Enhanced institutional success rates

---

## Future Enhancements

* Random Forest Classifier
* XGBoost Model
* Real-time Student Monitoring
* Cloud Deployment
* Mobile Dashboard
* Automated Academic Recommendations

---

visualization
<img width="466" height="371" alt="image" src="https://github.com/user-attachments/assets/e0fa9a9d-6b17-4c99-a7cd-bb697ef77b06" />
<img width="462" height="358" alt="image" src="https://github.com/user-attachments/assets/ca039ceb-2844-411b-93fb-5f564550c122" />
<img width="467" height="375" alt="image" src="https://github.com/user-attachments/assets/b992a52a-3042-423d-80c3-07e6edbf78a1" />
<img width="467" height="372" alt="image" src="https://github.com/user-attachments/assets/bc52f344-f802-4702-9dcb-6e4c39476600" />
<img width="473" height="380" alt="image" src="https://github.com/user-attachments/assets/c7d0e784-d0e2-4f78-8af4-561d969f0267" />
<img width="440" height="361" alt="image" src="https://github.com/user-attachments/assets/ecf234ad-a35a-4f0a-a2b1-13abc8590bf5" />
<img width="468" height="358" alt="image" src="https://github.com/user-attachments/assets/d1f1fc75-648b-47bd-9013-855944740664" />
<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/6c51d936-7dc2-440e-9fa9-34a229373aad" />
<img width="463" height="332" alt="image" src="https://github.com/user-attachments/assets/be9b392e-6176-425f-a1c3-42b5a54067c5" />
<img width="740" height="542" alt="image" src="https://github.com/user-attachments/assets/69fcc41c-3de8-4c2d-965d-ba1f3a58f273" />


## Conclusion

The Student Exam Pass Prediction System demonstrates how Machine Learning can be applied in the education sector to predict student outcomes and identify factors affecting academic performance. By combining EDA, Logistic Regression, and interactive dashboards, the project provides valuable insights that support educators in making informed decisions and improving student success rates.
