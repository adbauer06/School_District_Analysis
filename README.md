# School District Analysis

## Project Overview
The purpose of this project was to rerun a school district analysis that was previously done to look at trends in school performance.  This analysis is being rerun due to the discovery of information in the student data file that showed evidence of academic dishonesty, specifically regarding the reading and math scores for ninth-graders at Thomas High School.  

While this is being investigated, ninth-grade reading and math test scores for Thomas High School needed to be excluded from this analysis. 

The first task was to replace all reading and math test scores for students in ninth-grade at Thomas High School with null values while keeping the rest of the data intact.  Then the analysis was rerun and the following metrics recreated: 

1.  Summary of key metrics for the District
1.  Summary of key metrics by individual school
1.  Top and bottom 5 schools based on overall passing rate
1.  Average student math and reading scores by grade level
1.  School performance based on spending per student
1.  School performance based on school size
1.  School performance based on type of school


##  Resources
The following resources were used to complete this analysis:
- Data Sources:  
    - schools_complete.csv, containing district school information
    - students_complete.csv, containing student information
- Software:  Jupyter Notebook, Visual Studio Code, 1.58.2


## Analysis Results
Overall, removing the ninth-grade Thomas High School reading and math scores did not affect the original analysis as significantly as might have been expected.  Below are the new results of each each report/metric.  Any changes from the original analysis is noted.

- District Summary:  
    
    This report shows the key metrics for the school district as a whole.  Removing the ninth-grade reading and math scores for Thomas High School did not have a significant impact on the overall district-wide data.  There was just a slight decrease in passing percentages (-0.2% for passing math, -0.1% for passing reading, and -0.3% for overall passing).  

    ![District_Summary_updated.PNG](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/District_Summary_updated.PNG)
       
    
- Summary by School: 
    
    This report shows the key metrics for each individual school within the district.  At a school level, the overall performance for Thomas High School improved slightly by removing the ninth-grade scores.  Since we adjusted our student count to only include 10th through 12th grade students, this likely helped with keeping the passing percentages very close to what they were originally.

    ![School_Summary_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/School_Summary_updated.PNG)

    
- Summary of Top and Bottom Performing Schools:
    
    These reports show both the top five and bottom five performing schools, based on overall passing percentage.  Thomas High School maintained its spot as the second best performing school, with only a slightly higher overall percentage due to removing the ninth-grade scores.
 
    ![Top_5_Schools_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Top_5_Schools_updated.PNG)
    ![Bottom_5_Schools_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Bottom_5_Schools_updated.PNG)

    
- Math and Reading Scores by Grade:
    
    These reports show the breakdown of the average math and reading scores by school by grade-level.  Because they were removed, the ninth-grade scores for Thomas High School are displayed as "nan".  Otherwise, all other scores were unaffected.

    Math:     
    ![Math_Scores_by_Grade_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Math_Scores_by_Grade_updated.PNG)
    
    Reading:
    
    ![Reading_Scores_by_Grade_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Reading_Scores_by_Grade_updated.PNG)
    

    
- School performance based on School Spending:

    This report shows school performance by per-student spending ranges.  This report was not affected by the removal of the ninth-grade Thomas High School test scores.

    ![Scores_by_School_Spending_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Scores_by_School_Spending_updated.PNG)

    
- School Performance Based on School Size:

    This report looks at school performance in relation to school size.  This report was not affected by the removal of the ninth-grade Thomas High School test scores.

    ![Scores_by_School_Size_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Scores_by_School_Size_updated.PNG)

- School Performance Based on School Type:

    This report looks at school performance based on type of school.  This report was also not affected by the removal of the ninth-grade Thomas High School test scores.

    ![Scores_by_School_Type_updated](https://github.com/adbauer06/School_District_Analysis/blob/main/Resources/Scores_by_School_Type_updated.PNG)



 ## Summary
 In summary, the resulting changes caused by having to replace the ninth-grade test scores for Thomas High School were fairly insignificant.  
 - There was a slight decrease in the passing percentages in the district summary. 
 - There was a slight increase in performance percentages for Thomas High School in the school summary.  
 - Thomas High School's ranking within the the top performing schools remained the same, but with slightly improved performance percentages.  
 - The summaries by grade-level by school remained the same except that there were no scores included for ninth-grade for Thomas High School. 
 
