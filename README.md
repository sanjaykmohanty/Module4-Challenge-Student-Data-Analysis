# Module 4 Challenge - Student Data Analysis
## Overview
The purpose of this project is to perform a technical analysis of the student data and create a report based on the results.

The scope of the technical analysis includes:
- Collect the student data into a DataFrame
- Prepare a cleaned version of the DataFrame
- Summarize key pieces of the data
- Drill down into the data to analyze specific subsets
- Compare and contrast the data through grouping and aggregation functions

## Resources
Data Source: new_full_student_data.csv Software: Python 3.9.12, Jupyter Notebook 6.4.12

## Summary of the Findings:
### Collecting the Data
Pandas library was used to read the data in the CSV file into a DataFrame. Pandas head function was used to show the first five lines of a DataFrame to confirm that data loaded correctly into the DataFrame.

### Preparing the Data
- Student data CSV file had 1968 null values in "reading_score" column, and 982 null values in 'math_score' column. All records with null values were dropped for this analysis.
- Student data CSV file had 1836 duplicated rows. All duplicated rows were dropped for this analysis.
- Non-numeric data was removed from the "grade" column and the column type was changed from 'String’ to 'Integer'.

### Current Analysis
- The average math score is 64.676 which is higher than national average 47.8 (https://www.nationsreportcard.gov)
- The overall minimum reading score is 10.5, scored by a Dixon High School 10th grade student
- The average reading score for all students in grades 11 and 12 combined is 74.9 which is higher than the national average of 50.5 (https://www.nationsreportcard.gov)
- For Math and reading, Chatter school average scores are higher than Public school average scores   
- Montgomery High School has highest number of students at 2,038 and Chang High School has lowest number of students at 171.
- Based on the scores, Charter schools performed higher than the Public schools 

### Future Analysis Scope
- Total budget was 13,255,098,712 dollars of which 7,398,9907,33 (56%) was allocated to public schools and 5,586,190,799 (44%) was allocated to charter schools.
- Student count by school, school type, budget allocated per student, and student performance in terms of score, require additional analysis to understand the correlation between these data points.
