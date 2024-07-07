# Data-Preprocessing
This repository is created to show Data Preprocessing which includes Data Exploration, Data Cleaning, Data Analysis, Data Encoding and Features Scaling

## Employee-Data-Preprocessing
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning. 

Dataset adding here [Employee Dataset](https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing)

Data preprocessing Key Components to be fulfilled: 

## Data Exploration:

● Explore the data  

● List down the unique values in each feature and find its length. 

● Perform the statistical analysis and renaming of the columns. 

## Data Cleaning: 

● Find the missing and inappropriate values, treat them appropriately. 

● Remove all duplicate rows. 

● Find the outliers. 

● Replace the value 0 in age as NaN 

● Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode) 

## Data Analysis: 

● Filter the data with age >40 and salary<5000 

● Plotted the chart with age and salary which shows that employees aged 35 to 45 receive the highest salaries, with a peak around 40 years old.
  Salaries decrease for employees younger than 35 and older than 45.
  
● Count the number of people from each place and represented it visually showing Mumbai has the highest count of employees, followed by Calcutta and Chennai
  Nagpur and Bhopal has the lowest count among the listed locations.

## Data Encoding: 

● Convert categorical variables such as Employer, Employee_Location and Employee_country into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms. 

## Feature Scaling: 

After the process of encoding, perform the scaling of the features using 

● Standardscaler  

● Minmaxscaler.
