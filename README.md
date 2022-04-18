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


After removing the data, the analysis of the district and schools was repeated with the revised data set.
#  Analytical Results
-    ## How is the district summary affected?
The orginal data set contained data for fifteen schools with 39,170 students and a total budget or $24.6M.  The summary performance statistics are shown in the District Summary Table below.

<img src="Resources/District summary before.png" alt="Resources/District summary before.png" width="700" height="75">


The District Performance after removing the Thomas High School Freshman data is shown below.

<img src="Resources/Revised district summary.png" alt="Resources/Revised district summary.png" width="700" height="75">

The change reflects removing scores for 461 student scores from the District Summary data. Removing the scores by replacing them with "null" values casued the percent passing in reading, math and overall to drop substantially.

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
After replacing the THS Freshman math and reading scores with null values, you can see in the data frame prints for both that the "nan" appears instead of a score as shown in the Reading Scores by Grade frame below.  The math frame would look similar.

<img src="Resources/THS Reading Scores by Grade.png" alt="Resources/THS Reading Scores by Grade.png" width ="700" >

-    ## School Spending Comparison

Performance of schools by spending per student before -

<img src="Resources/performance by spending before.png" alt="Resources/performance by spending before.png" width="700" height="100">

After removing the scores the performance by spending categories was -

<img src="Resources/performance by spending after.png" alt="Resources/performance by spending after.png" width="700" height="100">

Thomas High School data is in the spending category of $631-$645 per student.  After removing the Freshman scores the performance in all categories improved.  

-    ## Shool Size Comparison
The school performance by size before removing the data

<img src="Resources/performance by size before1.png" alt="Resources/performance by size before1.png" width="500">

The school performance by size after is - 

<img src="Resources/performance by size after1.png" alt="Resources/performance by size after1.png" width="600">

Removing the Freshman scores did not change the performance of schools by size.
-    ## School Type Comparison
   The school performance by type, shown below, was prior to removing the THS Freshman data.
<img src="Resources/performance by type before1.png" alt="Resources/performance by type before1.png" width="500">  
The performance by type after removing the data is below.

<img src="Resources/performance by type after.png" alt="Resources/performance by type after.png" width="500"> 

There was not a measurable impact to the performance schores by type of shcool after removing the THS Freshman data.
