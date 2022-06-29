# School District Analysis with Python Using Jupyter Notebook

## Overview
The purpose is to analyze district school and student data to get insight into low and high performing schools. of the analysis is to A Colorado Board of Election employee has given the follwing tasks to complete the election audit of a recent local congressional election.

1. Replace ninth grade reading and math scores of Thomas high school with NaN due to evidence of alteration.  
2. Develop the district summary.
3. Develop the school summary.
4. Identify top five and bottom five performing schools based on the overall passing rate.
5. Show the average math score for each grade level from each school.
6. Show the average reading score for each grade level from each school.
7. The scores by school spending per student, by school size, and by school type.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Jupyter Notebook, Python 3.7.13, Visual Studio Code 1.68.1

## Results
The link to the script of original school district analysis.<br>
[Original school district analysis](/PyCitySchools.ipynb)<br>

The link to the script of school district analysis after replacing ninth grade reading and math scores of Thomas high school with NaN .<br>
[Modified school district analysis](/PyCitySchools_Challenge.ipynb)<br>

### DataFrame showing replacement of ninth grade reading and math scores of Thomas high school with NaN.
- Math and reading scores of 9th grade students of Thoman high school has been replaced to NaN.
- Analysis preformed with new data and not counting 9th grade students of Thoma high school for average math, reading and overall passing score.<br>

<figure>
    <figcaption>Thomas High School 9th Grade Math and Reading Score as NaN</figcaption>
    <img src="/Resources/student_data_thomas_school_9th_grade_nan.png" width="1112" height="541"
         alt="Thomas High School 9th Grade Math and Reading Score as NaN">
</figure> <br>

### School District Analysis

#### District Summary
- Distrcit summary changed as scores of 9th grade students of Thomas high school removed from the analysis.
- Average math score decreased from 79.0% to 78.9%.
- Average reading score unchanged at 81.9%.
- % student passing math decreased from 75.0% to 74.8%.
- % student passing reading decreased from 85.8% to 85.7%.
- % student overall passing decreased frin 65.2% to 64.9%.<br>

<figure>
    <figcaption>Original school district analysis</figcaption>
    <img src="/Resources/district_summary_original.png" width="2084" height="128"
         alt="Original school district analysis">
</figure> <br>

Modified School District Analysis.

<figure>
    <figcaption>Modified school district analysis</figcaption>
    <img src="/Resources/district_summary_modified.png" width="1059" height="114"
         alt="Modified school district analysis">
</figure> <br>

#### School Summary
- School summary of Thomas high school changed as scores of 9th grade students removed from the analysis.
- % student passing math decreased from 93.3% to 66.9%.
- % student passing reading decreased from 97.3% to 69.7%.
- % student overall passing decreased frin 90.9% to 65.1%.<br>

<figure>
    <figcaption>School summary</figcaption>
    <img src="/Resources/school_summary.png" width="1503" height="915"
         alt="School summary">
</figure> <br>

#### Top and Bottom Performing Schools Summary
- Top 5 and bottom 5 performing schools remain unchanged<br>

Top 5 Performing Schools

<figure>
    <figcaption>Top 5 Performing Schools</figcaption>
    <img src="/Resources/top_5_performing_schools.png" width="1487" height="377"
         alt="Top 5 Performing Schools">
</figure> <br>

Bottom 5 Performing Schools

<figure>
    <figcaption>Bottom 5 Performing Schools</figcaption>
    <img src="/Resources/bottom_5_performing_schools.png" width="1492" height="369"
         alt="Bottom 5 Performing Schools">
</figure> <br>

#### Score for each grade level from each school
- DataFrames show 9th grade math and reading scores for Thomas high school as NaN <br>

Average math score for each grade level from each school

<figure>
    <figcaption>Average math score by grade</figcaption>
    <img src="/Resources/average_math_score_grade_level.png" width="507" height="801"
         alt="Average math score by grade">
</figure> <br>

Average reading score for each grade level from each school

<figure>
    <figcaption>Average reading score by grade</figcaption>
    <img src="/Resources/average_reading_score_grade_level.png" width="502" height="772"
         alt="Average reading score by grade">
</figure> <br>

#### Scores by School Spending
- As spending per student increased; average math score, average reading score, %Passing Math, %Passing Reading and %Overall passing decreased.
- Negative coorealation between spending per student with performance of students.<br>

<figure>
    <figcaption>Scores by school spending</figcaption>
    <img src="/Resources/scores_school_spending_per_student.png" width="1854" height="393"
         alt="Scores by school spending">
</figure> <br>

#### Scores by School Size
- Schools with <2000 students show high performance.
- Schools with >2000 students show low performance.<br>

<figure>
    <figcaption>Scores by school size</figcaption>
    <img src="/Resources/scores_school_by_size.png" width="1854" height="393"
         alt="Scores by school size">
</figure> <br>

#### Scores by School Type
- Chater shcools performed better than district schools.<br>

<figure>
    <figcaption>Scores by school type</figcaption>
    <img src="/Resources/scores_school_by_type.png" width="1603" height="270"
         alt="Scores by school type">
</figure> <br>
