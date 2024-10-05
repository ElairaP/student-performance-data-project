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

![ethnicity pie chart](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/ethnicity%20pie%20chart.png)

- I also made pie charts for age and gender; the age charts show that the proportion of students in each age groups were very similar and the gender pie chart shows that the number of males and females were also very similar.

- To analyse the relationship between hours spent studying per week and GPA, I plotted a scatter graph. The graph showed no correlation between hours studied weekly and GPA.
- I also made a scatter graph to explore the relationships between number of absences and GPA.

- The scatter graphs shows that as the number of absences increases, the GPA of the student tends to decrease.

- I then explored the relationship between parental support and Grade Class
- To do this I first had to make subsets of the dataframe



