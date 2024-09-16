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

1. `Data Cleaning (Python)`
- Data Type Corrections: Ensured all columns have the correct data types.
- Handling Missing Data: Checked for any null values in the dataset.
- Outlier Detection: Examined the categorical data columns for outliers and inconsistencies.
2. `Data Analysis & Visualization (Power BI)`
- Exploratory Data Analysis: Performed in-depth analysis to find correlations between exam scores and other variables.
- Visualizations: Created charts and graphs to represent relationships between various factors and student performance.

## Outcomes



## Methodology

The analysis involves:
- **Data Cleaning**: Handling missing or inconsistent data.
- **Exploratory Data Analysis**: Understanding the distribution and relationships between variables.
- **Feature Selection**: Identifying the most significant factors affecting exam scores.
- **Modeling**: Building predictive models to estimate exam performance based on selected features.

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Kaggle for dataset

## Results

Summarize the main findings here, such as:
- Factors like `Hours_Studied` and `Parental_Involvement` are strongly correlated with higher exam scores.
- Peer influence and extracurricular activities have a moderate impact on performance.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook for analysis:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

## Acknowledgments

- Thanks to [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors/code) for providing the dataset.

---

You can adjust this template to better reflect your project's findings and details! Let me know if you'd like to add or edit any part.
