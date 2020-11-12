# School_District_Analysis

## Task - Aggregate the data and showcase the trends in school performance through high level snapshot of the school district's key metrics.
- Over view of metrics for each school
- Identify top five schools based on overall passing rates
- Identify bottom five schools based on overall passing rates
- Average math and reading scores in each grade level at each school
- School performance based on budget per student
- School performance based on school size
- School performance based the school type (Charter, District)

## Task for Challenge
- Academic dishonesty was reported for Thomas High School(THS) ninth graders specifically, reading and math grades.
- We will remove the ninth grade reading and math scores and refactor the data to uphold the state-testing standards.

## Results
- There were 461 freshman from THS (Out [10]) {not a required calc}.  There were 39170 students in the district with 100% completion of exams, making up a group .01% of the overall students tested.
- There were 11408 freshman in the district overall increasing the impact of the THS sample removed to .04%.
- Overall average scores were barely affected (See below Old/New Summary below).
- There was very little change to the overall passing avg of THS when the 9th grade was removed (less than a point).

## Scores Compared

### Old Scores Overall Summary
![Old_Summary](Resources/Old_Summary.PNG)

### New Scores Overall Summary
![New_Summary](Resources/New_Summary.PNG)

### Old Summary by School
![Old_District_Sum](Resources/Old_District_Sum.PNG)

### New Summary by School
![New_District_Sum](Resources/New_District_Sum.PNG)

### Top Five Change
- Old Top Five
![Old_Top_5](Resources/Old_Top_5.PNG)

- New Top Five
![New_Top_5_Single](Resources/New_Top_5_Single.PNG)

- The above graphics illustrate the change to the top five before and after removing the THS 9th grade from overall scores.
- Very little change is detected and the top five were not affected.

## Comments / Trends

Below are topics that would warrant further discussion by the school district administration and may warrant further investigation.

- It was interesting to evaluate the math and reading scores accross grades through individual schools.  Those grades did not change much from 9th to 12th grade.  To me, this would indicate systemic growth issues.  One would hope the grades would improve with continued education.

- Charter schools seem to out perform district schools with smaller class sizes, yet spending per student seems to be in the same range.

- Larger district schools typically spend more per student yet have typically lower test scores.

- District wide, reading scores trend higher than math scores.  Evaluating the math program may be in order.

### District Math Scores
![Dist_Math](Resources/Dist_Math)

### District Readign Scores
![Dist_Read](Resources/Dist_Read)




