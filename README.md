Project Title

Student Performance Analysis and Visualization using Pandas, NumPy, and Matplotlib

Project Description

This project creates a synthetic student dataset and performs data analysis to evaluate student performance. The dataset contains student details, marks, attendance, and internal marks. Various statistical analyses and visualizations are generated to gain insights into academic performance.

Objectives
Generate a student dataset using Python.
Analyze student academic performance.
Calculate total marks, average marks, and grades.
Identify top-performing students.
Compare performance based on department, gender, and year.
Visualize data using charts and graphs.
Technologies Used
Python
Pandas – Data manipulation and analysis
NumPy – Random data generation and numerical operations
Matplotlib – Data visualization
Dataset Information

The dataset contains 250 student records with the following attributes:

Column Name	Description
Student_ID	Unique student ID
Name	Student name
Gender	Male or Female
Department	CSE, IT, or ECE
Year	1st, 2nd, or 3rd Year
Maths	Mathematics marks
Science	Science marks
English	English marks
Attendance	Attendance percentage
Internal_Marks	Internal assessment marks
Total	Sum of subject marks
Average	Average marks
Grade	Performance grade
Grade Classification
Average Marks	Grade
80 and above	A
60 – 79	B
40 – 59	C
Below 40	Fail
Features Implemented
1. Dataset Generation
Generates 250 student records.
Randomly assigns departments, gender, and year.
Generates realistic marks using normal distribution.
2. Data Cleaning
Checks for missing values.
Ensures all marks remain between 35 and 100.
3. Performance Analysis
Calculates:
Total Marks
Average Marks
Grade
4. Statistical Summary
Mean
Median
Standard Deviation
Minimum and Maximum values
5. Student Ranking
Displays the Top 5 students based on total marks.
6. Department-wise Analysis
Calculates average performance for:
CSE
IT
ECE
7. Gender-wise Analysis
Compares average marks between male and female students.
8. Year-wise Analysis
Compares performance across academic years.
Visualizations
1. Bar Chart

Department-wise Performance

Shows average marks of each department.
2. Pie Chart

Gender Distribution

Displays percentage of male and female students.
3. Histogram

Average Marks Distribution

Shows frequency distribution of average marks.
4. Scatter Plot

Attendance vs Average Marks

Analyzes relationship between attendance and academic performance.
Sample Output
Department-wise Average
CSE : 69.14
ECE : 69.22
IT  : 68.20
Gender-wise Average
Female : 69.76
Male   : 68.03
Top Student
Student ID : 127
Total Marks : 277
Average : 92.33
Grade : A
Key Findings
No missing values were found in the dataset.
Female students performed slightly better on average.
ECE students achieved the highest departmental average.
No students received a Fail grade.
Higher attendance generally correlates with better academic performance.
Conclusion

This project demonstrates how Python can be used for educational data analysis. Using Pandas, NumPy, and Matplotlib, meaningful insights about student performance can be obtained through statistical analysis and visualizations. The project helps in understanding academic trends and identifying high-performing students efficiently.

Author

Student Performance Analysis Project
Developed using Python, Pandas, NumPy, and Matplotlib.
