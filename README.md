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
The orginal data set contained data for fifteen schools with 39,170 students and a total budget or $24.6M.  The summary performance statistics are shown in the District Summary Table below.

<img src="Resources/District summary before.png" alt="Resources/District summary before.png" width="700" height="75">

Thomas High School has an enrollment of 1,635 students and a per student spending of $638.  Thomas High is also medium size Charter school.  There were 461 Freshman student records removed from the analysis per the request from the District.





