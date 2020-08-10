# School_District_Analysis

## Overview of Project

### Purpose
The purpose of the school district analysis is to evaluate 15 schools for a variety of factors including but not limited to average student scores for reading/math, average student spending, type of school, performance by grade level, etc. Because the school board determined there's reasonable suspicion that the 9th grade Thomas High School's reading/math scores may have been manipulated, we have been asked in this exercise to alter the scores for Thomas High School's 9th graders to NaN and then evaluate the impact that it has on summary results. 

## Results

### Analysis of School/Student data

**How is the district summary affected?**

The district summary became slightly lower on average math score, average reading score, % Passing Math, % Passing Reading, and % Overall Passing after we replaced Thomas High School's 9th graders' reading and math scores to NaN. See pictures below for detail. 

District Summary prior to adjustment on Thomas High School:

![](Pictures/district_summary.PNG)  

District Summary after adjustment:

![](Pictures/district_summary_nothomas.PNG)

**How is the school summary affected?**

The school summary saw a tremendous percentage drop in the percentage of students passing math and reading. The Average Math and Reading score for the school was also slightly reduced. See the images in the below section for picture references. 

**How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?** 
The school's, in terms of ranking of all schools, saw a tremendous drop in Thomas High School's standing. Prior to the adjustment, Thomas High School was ranked 2nd with a 90.94% overall passing percentage, but the school's overall passing dropped to 65.07% after the above stipulated adjustment explained in the purpose section of this README

School standing prior to adjustment on Thomas High School:

![](Pictures/school_summary.PNG) 

School standing after adjustment: 

![](Pictures/school_summary_badthomas.PNG) 


**How does repacing the ninth-grade scores affect the following:**

  - **Math and reading scores by grade:** Math and reading scores for Thomas High School 9th graders are all "NaN" while 10th, 11th, 12th remains unaffected. See below picture depiction of math scores by grade before/after adjustment for Thomas High School. 
      
  ![](Pictures/math_bygrade.PNG) 
  ![](Pictures/math_bygrade_badthomas.PNG) 
  
  - **Scores by school spending:** Scores by school spending ranges saw a reduction in % Passing Math and % Passing Reading for the $630-644 bin. 
  
  ![](Pictures/spending_ranges.PNG) 
  ![](Pictures/spending_ranges_badthomas.PNG) 
  
  - **Scores by school size:** Scores by school size saw a reduction in % Passing Math and % Passing Reading for Medium (1000-2000) sized schools, indicating that Thomas High School falls within this particular bucket
  
  ![](Pictures/size_ranges.PNG) 
  ![](Pictures/size_ranges_badthomas.PNG)
  
  - **Scores by school type:** Scores by school type saw a reduction in Charter school % Passing Math, % Passing Reading, and % Overall Passing, indicating that Thomas High School is a charter type school. 
  
  ![](Pictures/school_type.PNG) 
  ![](Pictures/school_type_badthomas.PNG)
  
## School District Analysis Summary

  - Thomas High School's performance dropped from 2nd place for overall passing to 8th place
  - Medium sized schools (1000 to 2000) had a percentage reduction in math, reading, and overall passing percentages 
  - Schools that spent between $630 to $644 per student had a percentage reduction in math, reading, and overall passing percentages
  - Charter schools had a percentage reduction in math, reading, and overall passing percentages
