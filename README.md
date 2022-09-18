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
Pandas library was used to to read the data in the CSV file into a DataFrame. Pandas head function was used to show the first five lines of a DataFrame to confirma that data loaded correctly into the DataFrame.

### Preparing the Data
- Sudent data CSV file had 1968 null values in "rading_score" column, and 982 null values in 'math_score' column. All records with null values were dropped for this analyis.
- Student data CSV file had 1836 duplicated rows. All duplicated rows were dropped for this analysis.
- Non-numeric data was removed from the "grade" column and the column type was changed from 'String' type to 'Integer' type.

### Current Analysis
- The average math score of a student is 64.676
- The overall minimum reading score is 10.5, scored by a Dixon High School 10th grade student
- The average reading score for all students in grades 11 and 12 combined is 74.9
- For Math and reading, Chatter school average scores are higher than Public schools average scores   
- Montgomery High School has highest number of students at 2,038 and Chang High School has lowest number of students at 171.
- Charter schools are performing better than the public schools 

### Future Analysis Scope
- Total budget was 13,255,098,712 dollars of which 7,398,9907,33 (56%) was allocated to public schools and 5,586,190,799 (44%) was allocated to charter schools.
- Student count by school, school type, budget allocated per student, and student performance in terms of score, require additional analysis to understand the correlation between these data points.
