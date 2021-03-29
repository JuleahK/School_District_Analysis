# School_District_Analysis

##Overview

After completion of an analysis of a school district’s scores in math and reading based on varying factors such as size, budget, grade level, and school type, it was discovered that some of the data may been tampered with and therefore unreliable. It was the purpose of this project to rerun the analysis without the affected data to see how it affects the overall scores compared to the first analysis.
The data in question was the ninth grade math and reading scores from Thomas High School. To complete the new analysis, the scores for these were not taken out, but replaced with NaN such that they would still exist, but not be counted in the averages.

##Results

The summaries were affected thusly:

-District Summary: the % Passing Math and Reading dropped about 1% each, with the % Over Passing also dropping about 1%.

-School Summary:
 - % Passing Math: Significant changes here from Thomas High School from the original analysis, which showed 93% passing, with new analysis showing 67% passing.
 
 - % Passing Reading: Similar to math, the reading scores were greatly affected, with original analysis yielding 97% passing, and new analysis yielding 70% passing.
 
 - % Overall Passing: Original analysis put Thomas High School at 91% passing both math and reading. The adjusted analysis shows it at 65% passing. 
 
-Replacing the ninth grade scores affected the following:

 - Math and reading scores by grade: For Thomas High School grade 9, no scores are shown, all others remain the same
 
 - Scores by school spending: For the spending range $630-644, the scores were affected as follows: average scores unchanged, % Passing Math decreased from 73% to 67%, % Passing Reading decreased from 84% to 77%, and % Overall Passing was decreased from 63% to 56%.
 
 - Scores by school size: With Thomas High School being a “Medium” Sized school, these scores were affected thusly: average scores unchanged, % Passing Math decreased from 94% to 88%, % Passing Reading decreased from 97% to 91%, % Overall Passing decreased from 91% to 85%.
 
 - Scores by school type: Average scores remain the same, % Passing Math decreases from 94% to 90%, % Passing Reading decreases from 97% to 93%, and % Overall Passing decreases from 90% to 87%

##Summary

The areas affected by the changes to the ninth grade scores in math and reading at Thomas High School were the passing percentages. The changes were significant in the School Summary analysis, but still noticeable in the District Summary analysis. The % Passing Math decreased from 75% to 74%. The % Passing Reading decreased from 86% to 85%. The % Overall Passing decreased from 65% to 64%.
