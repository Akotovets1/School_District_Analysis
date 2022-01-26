# School_District_Analysis

## Overview of the school district analysis
The school district asked to analyze students data. They asked to take a snapshot of several key indicators.
After the report was compiled and reviewed by The School Board, it was determined that the data of the 9th grade of Thomas High School had apparently been altered. The School Board asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 
After that, it was needed to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

## Results

### Deliverable 1 The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs 
![9th_graders_THS_replaced_Nans](images/Aj_Check_student_for_NaN.png)


### Deliverable 2 Repeat the School District Analysis withpout the data of the 9th grade of Thomas High School

#### The district summary

##### Adjusted Analysis:
![Ajusted_district_summary](images/Aj_district_summary.png)

##### Original Analysis:
![Original_district_summary](images/O_district_summary.png)

#####  The district summary was affected:
- The Average Math Score has decreased slightly (from 79,0  to 78,9)
- Much of the other metrics remained the same because we remove a small portion of the data

#### The school summary


##### Adjusted Analysis:
![Ajusted_school_summary](images/Aj_School_Summary.png)

##### Original Analysis:
![Original_school_summary](images/O_School_Summary.png)

#####  The school summary was affected:
- There are only differences in the averages and percent passing at Thomas High School. Perentage of students passing math, reading  and overall passing percentage dropped.

#### The top 5 and bottom 5 performing schools, based on the overall passing rate

##### Adjusted Analysis:
Top 5:
![Ajusted_top_5](images/Aj_top_five_schools.png)

Bottom 5:
![Ajusted_bottom_5](images/Aj_bottom_five.png)

##### Original Analysis:
Top 5:
![Original_top_5](images/O_top_five_schools_by_Overall_Passing.png)

#####  The top and bottom 5 performing schools was affected:
- There are differences in the averages and percent passing at Thomas High School.
- Average Scores, % Passing and Overall Passing decreased for Thomas High School
- Bottom five high schools was unaffected

#### The average math score for each grade level from each school

##### Adjusted Analysis:
![Aj_average_math_scores](images/Aj_math_score.png)

##### Original Analysis:
![Or_average_math_scores](images/O_math_scores_by_grade.png)

#### The average reading score for each grade level from each school

##### Adjusted Analysis:
![Aj_average_reading_scores](images/Aj_reading_score.png)

##### Original Analysis:
![Or_average_reading_scores](images/O_reading_scores_by_grade.png)

##### The average math and reading scores for each grade level from each school was affected:
- Math and reading scores for ninth graders at Thomas High School were replaced with 'NaN'
- Thomas High School 10th, 11th, and 12th grade math scores remained the same

#### Scores by school spending per student
![Aj_spending_per_student](images/Aj_spend_per_stu.png)

Schools that spent less than $584 have the best math and reading scores.

#### The scores by school size
![Aj_spending_by_size](images/Aj_Scores_school_size.png)

Small and medium schools have a much better scores than large schools.

#### The scores by school type
![Aj_spending_by_type](images/Aj_score_by_school_type.png)

Charter schools have a better scores than the district schools.

## Summary
After the data was recalculated, the following changes occurred:
- Average Math Score dropped at Thomas High School
- % passing Math dropped at Thomas High School
- % passing Reading dropped at Thomas High School
- % Overall passing dropped at Thomas High School
