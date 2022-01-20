# School_District_Analysis

# Overview
This analysis was conducted to evaluate the performance of students and schools against state testing standards. The school board alleged that academic dishonesty permeated Thomas High School's ninth grade and requested that math and reading grades be withheld from the findings.

# Results
## District & School Summary
- The District Summary contained lower passing rates.
- The School Summary contained lower average math and average reading scores.

![School Summary](https://github.com/kramerkyle/School_District_Analysis/blob/main/Resources/school_summary.png)

## Ninth Grade
Replacing the ninth grade scores elicited
- Math and Reading Scores by Grade to show a NaN value for Thomas High School.
- Scores by School Spending to be lower within the $630-644 category.
- Scores by School Size did not appear to change given the formatting of the numbers. 
- Scores by School Type did not appear to change given the formatting of the numbers.

# Summary
In closing, after replacing the reading and math scores from Thomas High School with NaNs in the School District Analysis, our results changed. Specifically, we saw downward pressure on grades for Thomas High School and data sets that involved it. We saw a marginal decline occur within grades in the Scores by School data frame. Comparing schools by grade level, we see "nan" populate within the data frame, giving confidence that the appropriate scores were removed from the analysis. Finally, not all numbers visibly changed because of the formatting of the numbers. Within School Size and School type, results were formatted with either one or no decimal, and this choice will cause the nuance of the change to escape detection.
