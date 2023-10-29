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
- Finally, created the district summary data frame first by creating a dictionary with the required variables and then using pd.DataFrame to transform that into a data frame. Formatting code was provided to change the format of the total students and total budget columns.
- Then, the data frame was displayed. 
```
## School Summary
```

```
