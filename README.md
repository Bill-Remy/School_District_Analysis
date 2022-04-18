# School_District_Analysis

# Overview of the Project 
The Schoold District Analysis was originally scoped to provide an anlysis of reading, math and overall passing performance across fifteen schools in the district.  The original deliverables were as follows:
- Performance summary of the district showing reading, math and overall combined scores for the district.
- Summary of performance by school
- Average math scores for each school by grade
- Average reading scores for each school by grade
- Scores by each school grouped by spending per student, size of school and type of school

Before the final analysis was complete and provided to the district, the analytical team was notified of potential iregularities in one school and grade.  While the scores for the school and specific grade were not confirmed to be an academic violation, the district asked to have their data removed from the reporting.  Thus the team removed the data for Thomas High School(THS) 9th Grade and conducted the same analysis.
The District asked to see how the analysis was impacted by the removal of the THS Freshman data.  Specifically, they wanted to know:
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other school
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type
# Analytical Methods
In order to remove the THS Freshman data from the analysis the following steps were used:
- Locate all the THS Freshman records in the data set
- Set the math and reading scores to null
- Remove or drop the THS records with "null" values

After removing the data, the analysis of the district and schools was repeated with the revised data set.
#  Analytical Results
-    ## How is the district summary affected?
The orginal data set contained data for fifteen schools with 39,170 students and a total budget or $24.6M.  The summary performance statistics are shown in the District Summary Table below.

<img src="Resources/District summary before.png" alt="Resources/District summary before.png" width="700" height="75">


The District Performance after removing the Thomas High School Freshman data is shown below.

<img src="Resources/Revised district summary.png" alt="Resources/Revised district summary.png" width="700" height="75">

The change reflects removing scores for 461 students from the District Summary data.  The average reading scores for THS Freshman would have been 87.4 which is significantly higher than the district average while their average math scores were at the district average if 81.9.  The THS Freshman had a percentage passing greater than 90% for all three categories which was much greater than the district average.  While not conclusive of any academic misconduct the performance of the THS Freshman is better than would normally be expected.

-    ## How is the school summary affected?
The Thomas High Schools individual summary data prior to removing the freshman scores is shown below:

<img src="Resources/School summary header.png" alt="Resources/Schol summary header.png" with="300">
<img src="Resources/THS Summary before.png" alt="Resources/THS Summary before.png" width="1000" >

After removing the scores for the freshman, the revised reading and math performance is in the following table.

<img src="Resources/School summary header.png" alt="Resources/School summary header.png" with="300">
<img src="Resources/THS Summary after.png" alt="Resources/THS Summary after.png" width="11000" >

The THS specific performance data is similar to the District Summary in the impact of removing the scores.  The THS Freshman were performance significantly above the rest of the school in reading and math.  Their passing percentages were much higher since after removing their scores the rest of the school passing percentage was much lower.

-    ##  THS Performance to Other Schools
After removing the scores, THS performance relative to other schools dropped measuably in the percentage passing performance.  In Math, Reading and Overall percents prior to removing the data, THS was above 90% in all three measures.  After removing the data, their percantage passing dropped to 66-69% ranges.  The scores removed would have been substantially higher than the rest of the school.

-    ##  Math and Reading by Grade

-    ## School Spending Comparison

-    ## Shool Size Comparison
The school performance by size before removing the data - <img src="Resources/performance by size before.png" alt="Resources/performance by size before.png" width="600">
-    ## School Type Comparison
   The school performance by type, shown below, was prior to removing the THS Freshman data.
<img src="Resources/performance by type before1.png" alt="Resources/performance by type before1.png" title="Performance by Type - Before" width="500">  
The performance by type after removing the data is below.

<img src="Resources/performance by type after.png" alt="Resources/performance by type after.png" width="500"> 

There was not a measurable impact to the performance schores by type of shcool after removing the THS Freshman data.
