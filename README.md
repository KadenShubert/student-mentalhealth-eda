# Student Mental Health EDA - Assignment
Performing Data Analysis, Data Cleaning, and Machine Learning on [this](https://www.kaggle.com/datasets/shariful07/student-mental-health) Student Mental Health dataset.

### Exploratory Data Analysis of Student Mental health with depression prediction

This notebook aims to identify and illustrate any correlations between a student's mental health, academic program, academic performance, and personal factors.

### Problem Statement

Mental health issues are common among students but often go untreated or unnoticed. This project aims to reduce the levels of both unnoticed and untreated issues by analyzing this dataset to identify relationships within the collected data and use Machine Learning to bolster that analysis and provide a way to identify if a student may be dealing with one of these conditions.

### Solution

For the data cleaning the pandas library was used to store and modify the data. For the data analysis seaborn pairplot, countplot, and histograms were used to visualize the distribution and relations of the features. For the Machine Learning, I utilized a Random Forest Classification model as it gave the best results during cross-validation.

### Repository Structure

The repository contains the following files:

💾 Student_Mental_health.csv: The dataset contains information about students including Gender, Age, Marital Status, and whether they have Depression, Anxiety, Panic Attacks, or have sought treatment. Along with their schooling information GPA, Year of Study, and course

📔 Student_Mental_Health_Analysis.ipynb: A jupyter notebook containing all Data Analysis, Data Cleaning, and Machine Learning. This notebook is only intended to be used with the provided dataset
