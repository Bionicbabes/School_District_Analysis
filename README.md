**# School_District_Analysis**
------------------------------

**# Overview**

The school board has notified me that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to me for help. The school board has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, the school board would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


- **How was the district summary affected ?**
------------------------------

The effect on the district averages are subtle, by removing the data we see a decrease across all the values.  Math score decreased by 0.1%, reading stayed the same, decrease in passing math % by 0.2, decrease in passing reading % by 0.3, decrease in overall passing % by 0.1.

**Original Distric Data Frame**
![Original_district_summary.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Original_district_summary.PNG)

**Modified Distric Data Frame**

![Modified_district_summary.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Modified_district_summary.PNG)




- **How was the school summary affected ?**
- ------------------------------

We found that there were a total of 461 students from Thomas High School.  All of their scores have been removed from the over totals student going from 39,170 students to 38,709 students.  Data frames show an ~ 25 to 30 % increase in the passing scores from the Thomas High School. 

**Original School Data Frame**

![Original_per_school_summary.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Original_per_school_summary.PNG) 

**Modified District Data Frame**
![Modified_per_schools_summary.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Modified_per_schools_summary.PNG)

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
------------------------------

Although this did not effect the averages at all the overall passing percentage increased dramatically and takes Thomas High School from being 8th in the disctric to being 2nd best in the district
 
**Original Top Schools data Frame**
![Top_school_by_overall_score_original.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Top_school_by_overall_score_original.PNG)

**Modified Top Schools Data Frame**

![Top_school_by_overall_score_modified.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Top_school_by_overall_score_modified.PNG)

- **How does replacing the ninth-grade scores affect the following:**
------------------------------

- Math and reading scores by grade
Looking at the data all the the averages across all grade are very similar ranging from 83.2 to 84.0 for the top tear schools, but what is interesting is when you take out the ninth graders and decrease the total number of students the passing percentages all increase significantly.  Thomas High school are very consistent from grade to grade the differentiator is the school size for overall performance.

**Math Scores by Grade data Frame**

![Math_scores_by_school.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Math_scores_by_school.PNG)

**Reading Scores by Grade data Frame**

![Reading_scores_by_school.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Reading_scores_by_school.PNG)


- **Scores by School Spending**
The spending ranges did not change and Thomas High School falls into the bucket of $630-644.  No other changes were made to the data so this is the only bucket that was effected all the passing percentages went up for all values. 

**Scores by School Spending Original data Frame**

![spending_modified.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/spending_modified.PNG)

**Scores by School Spending Modified data Frame**

![spending_original.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/spending_original.PNG)

- **Scores by school size** 

The School size with out the 9th grader went from 1,635 students to 1,174, this was not a big enough reduction to move Thomas High School into a different bin.  The only effected score are in the Medium (1000-2000) bin were all passing scores increased due to the reduction in the total students in the demoninator when calculating he percentages. 

**Scores by School Size Original data Frame**

![School_Size_Original.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/School_Size_Original.PNG)


**Scores by School Size Modified data Frame**

When looking at the school type Thomas is charter school and will only effect the charter school type. Passing pecentages increased for math, reading and overall. 

![School_Size_Modified.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/School_Size_Modified.PNG)

- **Scores by School Type**

**Scores by School Type Original data Frame**

![Scores_by_school_type_modified.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Scores_by_school_type_modified.PNG)

**Scores by School Type Modified data Frame**

![Scores_by_school_type_original.PNG](https://github.com/Bionicbabes/School_District_Analysis/blob/main/Resources/Scores_by_school_type_original.PNG)

- **Summary:**
------------------------------

This report goes over in detail the effects of removing the 9th graders from Thomas High School, but overall the effect are seen in all of the anlaysis.  This is do to how percentages work by removing the students we are decreasing the demoninator in the equation and therefor increasing all the passing percentage, this is the inverse proportion property of percentages.  Although the percentages have changed and effected our analysis across all metrics the averages for math and reading have stay relatively the same due to the small standard deviation within the sample school.  Thomas High School definetly looks better now that the 9th graders have been removed going from 8th best in the distric to 2nd best.  Population size seems to be the driving factor with the larger schools having much lower passing percentages.

