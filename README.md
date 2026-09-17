# Student Performance Analysis

A beginner-level data science project exploring factors associated with student exam performance and comparing different regression models for exam score prediction.

## Project Overview

This project analyzes a dataset containing information about students' academic performance, study habits, attendance, and other background factors.

The main goal is to explore the relationships between these variables and examine how well different regression models can predict students' exam scores.

## Dataset

The dataset contains **6,607 student records** and includes variables such as:

* Hours Studied
* Attendance
* Previous Scores
* Sleep Hours
* Tutoring Sessions
* Parental Involvement
* Motivation Level
* Teacher Quality
* Family Income
* School Type
* Exam Score

## What I Did

* Loaded and explored the dataset using Pandas
* Checked and handled missing values
* Encoded categorical variables
* Performed exploratory data analysis
* Created visualizations using Matplotlib and Seaborn
* Used `Exam_Score` as the target variable
* Split the data into training and testing sets
* Compared three regression models:

  * Linear Regression
  * Decision Tree Regression
  * Random Forest Regression
* Evaluated the models using MAE and R²

## Model Results

| Model             |  MAE |     R² |
| ----------------- | ---: | -----: |
| Linear Regression | 0.49 | 73.14% |
| Decision Tree     | 1.85 | 16.55% |
| Random Forest     | 1.25 | 61.09% |

In this experiment, Linear Regression produced the lowest MAE and highest R² among the three tested models.

## Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## Notes

This project was developed as a learning project to practice data cleaning, exploratory data analysis, data visualization, and introductory machine learning techniques.

