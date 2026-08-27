Student Performance Analysis Using R
Project Overview

Student Performance Analysis is a data analysis project developed using R programming. The main purpose of this project is to analyze student academic data and identify patterns related to study hours, attendance, assignment scores, exam marks, and final results.

Objectives
Analyze student academic performance.
Calculate average study hours and exam marks.
Analyze student attendance.
Identify Pass and Fail patterns.
Analyze the relationship between study hours and exam marks.
Analyze the relationship between attendance and exam marks.
Visualize student performance using graphs.
Generate meaningful insights from the dataset.
Dataset

The dataset contains the following attributes:

Attribute	Description
Student_ID	Unique ID of the student
Age	Age of the student
Gender	Gender of the student
Study_Hours	Average study hours
Attendance	Attendance percentage
Assignment_Score	Assignment marks
Exam_Marks	Final examination marks
Result	Pass or Fail
Technologies Used
R Programming
RStudio
CSV Dataset
Base R Visualization
Data Analysis Process

Collect Data → Clean Data → Analyze Data → Find Patterns → Visualize Results → Generate Findings

Data Preprocessing

The dataset is checked for:

Missing values
Duplicate records
Incorrect or incomplete data

R functions such as is.na(), na.omit() and duplicated() are used for preprocessing.

R Functions Used
read.csv()
print()
str()
summary()
mean()
table()
aggregate()
cor()
hist()
barplot()
plot()
Analysis Performed
Average Performance

The project calculates:

Average age
Average study hours
Average attendance
Average exam marks
Result Analysis

The number of students who Passed and Failed is calculated using a frequency table.

Study Hours Analysis

The relationship between study hours and exam marks is analyzed to identify performance patterns.

Attendance Analysis

Attendance and exam marks are compared to identify academic performance patterns.

Gender-wise Performance

Average exam marks are calculated for different gender groups.

Visualizations

The project generates:

Exam Marks Distribution
Student Result Distribution
Attendance Distribution
Study Hours vs Exam Marks
Gender-wise Average Exam Marks
Conclusion

Student Performance Analysis using R provides an effective way to analyze academic data. R can be used for data cleaning, statistical calculations, frequency analysis, correlation analysis, and visualization.

The identified patterns can help understand student performance and support better academic decision-making.
