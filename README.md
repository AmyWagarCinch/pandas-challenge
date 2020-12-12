# pandas-challenge: PyCitySchools

For this assignment, we've been asked to analyze fictional school district-wide standardized test results. We are given access to every student's math and reading scores, as well as various information on the schools they attend. Our responsibility is to aggregate the data to and showcase obvious trends in school performance.
My final report includes each of the following:

District Summary

A high level snapshot (in table form) of the district's key metrics, including:

Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)

School Summary

An overview table that summarizes key metrics about each school, including:

School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)

Top Performing Schools (By % Overall Passing)

A table that highlights the top 5 performing schools based on % Overall Passing. Includes:

School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)

Bottom Performing Schools (By % Overall Passing)

A table that highlights the bottom 5 performing schools based on % Overall Passing. Includes all of the same metrics as above.

Math Scores by Grade**

A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade

A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending

A table that breaks down school performances based on average Spending Ranges (Per Student). I used 4 reasonable bins to group school spending. I've included in the table each of the following:

Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)

Scores by School Size

Same as above, but this time I've grouped schools based on a reasonable approximation of school size (Small, Medium, Large).

Scores by School Type

Same as above, but this time I've grouped schools based on school type (Charter vs. District).

In this exercise, I used the pandas library and Jupyter Notebook.

The data analysis provides several intriguing observable trends. There appears to be a negative correlation between school funding per student and standardized test performance. There also appears to be some interesting insights regarding standardized test performance differences between charter and district schools with charter school students performing considerably better on standardized tests. These trends warrant further investigation into external factors that may exist in the community and a deeper look at what standardized testing is measuring.
