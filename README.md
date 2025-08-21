# Student Performance Prediction using Regression

## Project Overview
This project focuses on predicting students' exam scores based on various academic, personal, and environmental factors. By applying **Linear Regression** and **Polynomial Regression**, we aim to understand the relationship between different features (like study hours, sleep, parental involvement, etc.) and student performance.

## Dataset
The dataset contains the following features:

- **Hours_Studied**
- **Attendance**
- **Parental_Involvement**
- **Access_to_Resources**
- **Extracurricular_Activities**
- **Sleep_Hours**
- **Previous_Scores**
- **Motivation_Level**
- **Internet_Access**
- **Tutoring_Sessions**
- **Family_Income**
- **Teacher_Quality**
- **School_Type**
- **Peer_Influence**
- **Physical_Activity**
- **Learning_Disabilities**
- **Parental_Education_Level**
- **Distance_from_Home**
- **Gender**
- **Exam_Score** (Target Variable)

## Project Workflow
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Splitting the dataset into training and testing sets  

2. **Model Building**  
   - Linear Regression  
   - Polynomial Regression  

3. **Evaluation Metrics**  
   - Root Mean Squared Error (RMSE)  
   - R² Score  

## Results
- **Linear Regression**  
  - RMSE: *2.09*  
  - R² Score: *0.69*  

- **Polynomial Regression (Degree 2)**  
  - RMSE: *1.86*  
  - R² Score: *0.76*  

Polynomial Regression performed better, showing a stronger fit to the data.

##  Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
