# Student Analysis

## Overview

This project explores factors affecting student exam scores using a dataset sourced from Kaggle. The aim is to identify relationships between exam performance and various factors like study habits, parental involvement, extracurricular activities, and more.

## Dataset

The dataset, obtained from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors/code), includes the following columns:

- `Hours_Studied`
- `Attendance`
- `Parental_Involvement`
- `Access_to_Resources`
- `Extracurricular_Activities`
- `Sleep_Hours`
- `Previous_Scores`
- `Motivation_Level`
- `Internet_Access`
- `Tutoring_Sessions`
- `Family_Income`
- `Teacher_Quality`
- `School_Type`
- `Peer_Influence`
- `Physical_Activity`
- `Learning_Disabilities`
- `Parental_Education_Level`
- `Distance_from_Home`
- `Gender`
- `Exam_Score`

## Project Goals

The key objectives of this analysis include:

1. Investigating how various factors like study habits and attendance influence exam scores.
2. Identifying the strongest predictors of student performance.
3. Visualizing trends and patterns in student performance based on these factors.

## Process

1. **Data Cleaning (Python)**
- Data Type Corrections: Ensured all columns have the correct data types.
- Handling Missing Data: Checked for any null values in the dataset.
- Outlier Detection: Examined the categorical data columns for outliers and inconsistencies.
2. **Data Analysis & Visualization (Power BI)**
- Exploratory Data Analysis: Performed in-depth analysis to find correlations between exam scores and other variables.
- Visualizations: Created charts and graphs to represent relationships between various factors and student performance.

## Outcomes

- The analysis is based on data from 6,607 students, who come from diverse schools and backgrounds. This variety provides a comprehensive view of factors influencing student performance across different contexts.
![1](https://github.com/user-attachments/assets/4e797108-08a1-4fcc-8018-01668da1984b)

- Looking at the gender distribution, we find that 57.33% of the students are male, with the remaining being female. When comparing exam results by gender, the average exam score for male students is 67.23, while for female students, it is 67.24. Additionally, the average scores for previous exams are nearly identical for both genders. There is no significant difference in the minimum and maximum results between genders. Therefore, we can conclude that there is no notable difference in performance between male and female students.

![2](https://github.com/user-attachments/assets/da84f236-63b3-4d4c-84c0-47833fc1e2fb)
![3](https://github.com/user-attachments/assets/56c1eae2-fd37-4ed8-98bd-2f2717f21fb4)

- Next, I examined the effect of parental involvement on exam results. The average exam scores for different levels of parental involvement are as follows: high level – 68.09, medium level – 67.10, and low level – 66.36. These results indicate that parental involvement does not have a significant impact on exam scores.

![4](https://github.com/user-attachments/assets/ed7afa49-f5f7-4df9-9087-f6bf9064581f)

- Now, let's examine the effects of school type and teacher quality on student performance. As shown in the first table, the average exam score for public schools is 67.21, while for private schools, it is 67.29. The average scores for previous exams are also similar across both types of schools.

- In the second table, teacher quality is categorized into high, medium, and low levels. The average exam scores for these categories are very similar, indicating no significant differences in performance based on teacher quality.

Therefore, the analysis suggests that both school type and teacher quality do not have a significant impact on exam results.

![5](https://github.com/user-attachments/assets/222a3f5b-9a99-4477-acab-15adc7154858)
![6](https://github.com/user-attachments/assets/be2bbb84-661b-488f-80bd-948e54c13407)

- In the scatter plot, we see a clear trend up to an exam score of 80: as study hours increase, exam scores also tend to increase. However, for exam scores in the range of 80 to 100, no significant trend is observed. This suggests that, for students scoring between 80 and 100, prior knowledge may play a more crucial role than additional study time before the exam. Conversely, for students scoring between 0 and 80, hours of study have a more noticeable impact on their exam scores.

![7](https://github.com/user-attachments/assets/dfca1721-137f-4320-b1b1-81e8a5e5fb25)

- Lastly, I examined the effect of attendance on exam scores. Attendance is measured as a percentage, with a minimum of 67% and a maximum of 100%. By calculating the average exam score for each attendance percentage, we observed a general trend: as attendance increases, the average exam score also tends to increase. This indicates that higher attendance is generally associated with better exam performance.

![8](https://github.com/user-attachments/assets/8aac1be0-4748-42f9-8fff-1ea796d0c5d1)

## Summary

In this project, I examined various factors affecting student performance on exams. Analysis of gender distribution showed no significant difference in exam results between genders. Similarly, parental involvement, school type, and teacher quality did not have a notable impact on exam scores.

However, hours of studying demonstrated a positive trend up to an exam score of 80. Beyond this score range, additional study hours did not show a substantial effect. The most significant factor identified is attendance; as attendance increases, so does the average exam score.

In conclusion, the primary factors influencing exam scores are student effort, reflected in attendance and study hours, rather than external factors such as parental involvement, school type, or teacher quality.


