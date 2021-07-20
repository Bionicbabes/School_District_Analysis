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
