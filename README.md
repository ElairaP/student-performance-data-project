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
### Demographic
- I first analysed the demographic of the dataset

![ethnicity pie chart](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/ethnicity%20pie%20chart.png)

- I also made pie charts for age and gender; the age charts show that the proportion of students in each age groups were very similar and the gender pie chart shows that the number of males and females were also very similar.

### Hours Spent Studying Per Week and GPA
- To analyse the relationship between hours spent studying per week and GPA, I plotted a scatter graph. The graph showed no correlation between hours studied weekly and GPA.

### Number of Absences in the School Year and GPA
- I also made a scatter graph to explore the relationships between number of absences and GPA.

![absences scatter graph](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/absences%20and%20GPA.png)

- The scatter graphs shows that as the number of absences increases, the GPA of the student tends to decrease.

### Parental Support and Grade Class
- I then explored the relationship between parental support and Grade Class
- To do this I first had to make subsets of the dataframe

![parental supports subsets](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/parental%20support%20subsets.png)

![parental supports pie charts](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/parental%20support%20and%20GPA%20pie%20charts.png)  

- The pis charts show that students who had no parent support from their parents had the largest proportion of F class grades
- Whereas students that received a high amount of parental support had the smallest proprtion of F class grades and the largest proportion of A class grades.

### Tutoring and Grade Class
- To explore this relationship I had to create subsets of the dataframe to separate those who had received tutoring and those who had not.

![Tutoring pie chart](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/tutoring%20and%20GPA.png)  

-The graph shows that among the students that receive tutoring, there is a smaller proportion of students that receive F class grades and a larger proportion that receive A class grades compared to students who don't receive tutoring.

### Parental Education and Grade Class
- To explore this relationship I created a bar graph and pie charts
![Parental education bar code](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/parental%20education%20bar%20code.png)  

![Parental education bar chart](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/parental%20education%20bar%20plot.png)  

- The bar graph shows that the proportion of the different paretnal education levels are roughly similar among all grade classes, suggesting no correlation between parental education and grade class.

![Prental Educationa pie charts](https://github.com/ElairaP/student-performance-data-project/blob/main/screenshots/parental%20education%20pie%20charts.png)  

- The pie charts show that among the students whose parents have an education level higer that a Bachelor's degree, there is a larger proportion of F class grades and a smaller proportion of A class grades compared to the other groups.


