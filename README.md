# pandas-challenge
## PyCity Schools Analysis
```
I began by writing out a summary of the analysis being performed on the PyCity Schools.
```
## PyCity Schools Conclusions
```
I made a few conclusions about the data and variables correlating to school performance.
```
## Reading and Merging CSV files
```
- Used the provided code to read in the schools_complete.csv and students_complete.csv. The provided code also merged the two CSVs on the school_name columns.
- The first 5 rows of the newly merged CSVs were displayed using the head() function.
```
## District Summary
```
- In this section, the total number of schools value was retrieved by using the len function on the unique values in the school_name column.
- Then, the total number of students value was retrieved by using the len function on the unique values in the Student_ID column.
- The total budget was acquired using the unique function on the budget column and taking the sum of those values.
Average math and reading scores were calculated by taking the mean of the math_score and readin_score columns respectively.
- I used the code provided to calculate the percentage of students passing math. This same code was used to find the percentage of students passing reading by simply changing out math for reading in the code.
- Used the provided code to find the overall passing students percentage.
- Finally, created the district summary data frame first by creating a dictionary with the required variables and then using pd.DataFrame to transform that into a data frame. The formatting code was provided to change the format of the total students and total budget columns.
- Then, the data frame was displayed. 
```
## School Summary
```
- First, created code that looked into the school_data file and set the index to the school_name column and only included the type column to select all of the school types.
- Next, grouped by the school_name column in the school_data_complete file and took the count of student ID to get the total number of students per school.
- Then, grouped by school_name again and took the sum of the budget column to get the total budget. Divided this by the per_schools_count to get budget per school. Then took the new per_school_budget variable and divided by the per_schools_count variable to get the budget per student per school. 
- Once again grouped by school_name and took the average of the math_score and reading_score columns respectively. 
- Used code from the district summary section to calculate the number of students passing both math and reading (over 70%). 
- After, used the provided code to calculate the number of students passing both reading and math per school.
- Used the provided code to calculate passing rates for math, reading, and overall.
- Created another dictionary with the required variables, and then used a pd.DataFrame function to create a data frame. Used the provided formatting code and then displayed the data frame. 
```
## Highest-Performing Schools (by % Overall Passing)
```
- X
- X
- X
- X
- X
- X
```
