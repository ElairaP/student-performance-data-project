# Student Performance Data Analysis Project
This project involves using python to analyse a dataset to see if there are any correlations between student academic performance and certain factors such as parental support, hours spent studying per week etc. The dataset used for this project was found on kaggle. https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset  
This dataset is owned by Mr. Rabie El Kharoua

## Preparing The Data
- After loading the dataset I checked for any duplicates in the data. No duplicates were found.
- To check for any incorrect or missing values in the dataset I used the unique function on columns with discrete data and checked the ranges for columns with continuous data.
- No incorrect or missing values were found
- I rounded the values in the StudyTimeWeekly and GPA columns to 1 d.p and 2 d.p respectively to make the data in those columns easier to work with.

### Mapping values
- For some columns, the data in the dataset were encoded as numbers and the key which describes what the numbers in each column means was put on kaggle.
- To make the dataset easier to understand I mapped the encoded data to their actual value.

![Mapping screenshot](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/mapping%20values%20screenshot.png)

## Analysing and Visualising the Data
- I first analysed the demographic of the dataset
