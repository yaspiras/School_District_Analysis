# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.
We were informed that the file used for the original Student District Analysis, students_complete.csv file, shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards.

For this reason, the math and reading scores for Thomas High School were replaced with NaNs (not a number) while keeping the rest of the data intact. After replacement with NaNs, the school district analysis was redone.  

## Results: Changing the Thomas High School 9th Grade math and reading scores affected the following:
- **District summary: no significant change**
  -  **Orginal:**
       % Passing Math-75.0	% Passing Reading-85.8 % Overall Passing-65.2
  -  **Re-analysis:**
       % Passing Math-74.8	% Passing Reading-85.7 % Overall Passing-64.9
- **School summary: no significant change**
- **Thomas High School Performance relative to other schools:** Thomas High School is still the top 2 from all schools.
  -  **Orginal:**
       % Passing Math-93.3	% Passing Reading-97.3 % Overall Passing-90.9
  -  **Re-analysis without adjusting total student count:**
       % Passing Math-66.9	% Passing Reading-69.7 % Overall Passing-65.1
  -  **Re-analysis with adjusting of total student count by removing 9th-Grade student count:**
       % Passing Math-93.2	% Passing Reading-97.0 % Overall Passing-90.6
- **Math and reading scores by grade:** math and reading scores by all other grades were not affected.  9th grade scores          were not calculated because scores were replaced with NaNs
- **Scores by schools spending:** no significant change
- **Scores by school size:** no significant change
- **Scores by school type:** no significant change
  
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
After changing the Thomas High School 9th grade math and reading scores to NaN and redoing district and school analysis, we found that there was no significant change from the original numbers.  Although there was no significant change in the result, it was still important that the re-analysis was done to see if there was an actual effect on the results. Re-analysis of data is due diligence after knowing that there was alleged dishonesty that occured. 
