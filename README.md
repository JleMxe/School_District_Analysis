# Overview School_District_Analysis
    An analysis of the School District has been requested. However, due to evidence of academic dishonesty discovered amongst the Thomas High School 9th grade class, the math and reading scores for that class have been requested to be replaced with NaN(s) so that the data associated with that particular class will not be included in the result.

# School District Analysis Deliverables
- Replace the ninth grade reading and math scores from Thomas High School with NaN(s).
- Repeat the school district analysis with the cleansed data and highlight the differences.
    - Discuss the affect on the district summary.
    - Discuss the affect on the school summary.
    - Discuss the affect of removing the 9th graders scores on Thomas High School's performance in relation to the other schools.
    - Discuss how replacing the 9th graders scores affected the following:
        - Math and reading scores by grade.
        - Scores by school spending.
        - Scores by school size.
        - Scores by school type

# Data sources for School District Analysis
- students_complete.csv
- schools_complete.csv

# School District Analysis Results
The first step in completing the requirements was to replace all the math and reading scores from 9th grade class of Thomas High School. The was completed suing the loc command with results as shown below.

![School District Analysis Outputs](/Supporting_Data/THS_scores_replacement.png)

The graphic shown below contains a district summary before and after the math and reading scores for Thomas High School (THS) were removed. Note that the student count is the same in both as the students were not removed, just their grades. The effect of removing the grades increased the average math score by .1 and consequently increased the percent passing math by 0.2%. While the average reading score, at 1 decimal place precision, was not affected, the percent passing reading did go up .3%. As a result, the overall passing percentage went up by 0.1%.

![School District Analysis Outputs](/Supporting_Data/District_Summary_Comparison.png)

In the graphic below, the school summary before and after THS's math and reading scores were removed. 

![School District Analysis Outputs](/Supporting_Data/School_Summary_Comparison.png)

In order to facilitate viewing, the below graphic is the school summary for THS only.
By showing the before and after in close proximity as well as several decimal places of precision, one can see the difference in the scores and percentages and see that it is minimal.
![School District Analysis Outputs](/Supporting_Data/School_Summary_Comparison_THS.png)

The below graphic shows the top 5 schools in the district. Removing the scores for the 9th graders had no effect on the ranking of THS as it placed second in both scenarios.

![School District Analysis Outputs](/Supporting_Data/School_Ranking_Comparison_THS.png)

To further compare results, below is shown a graphic displaying the math and reading scores by grade for all schools. The only effect of removing the THS 9th graders scores is there being a nan (scores were replaced with this prior to re-analysis to eliminate the potential effect of academic dishonesty) in the 9th graders field.

![School District Analysis Outputs](/Supporting_Data/Math_Reading_By_Grade_Comparison.png)

The graphic below shows the before and after for scores grouped by spending ranges. There was no effect to 1 decimal place of precision.

![School District Analysis Outputs](/Supporting_Data/Scores_By_Spending_Comparison.png)

The graphic below shows the before and after for scores grouped by school size ranges. There was no effect to 1 decimal place of precision.

![School District Analysis Outputs](/Supporting_Data/Scores_By_School_Size_Comparison.png)

The graphic below shows the before and after for scores grouped by school type. There was no effect to 1 decimal place of precision.

![School District Analysis Outputs](/Supporting_Data/Scores_By_School_Type_Comparison.png)


# School District Analysis Summary

The analysis performed revealed that there were indeed changes to the district summary after removing THS's 9th grade math and reading scores. However, the magnitude was minimal as follows:
- Average math score increased by .1.
- Average reading score saw no change.
- % passing math increased by .2%.
- % overall passing increased by .1.
- There was no effect on school ranking.
- There was no change in scores grouped by spending.
- There was no change in scores grouped by school size.
- There was no change in scores by school type.

To conclude, while the suspicion of academic dishonesty may or may not be true, the effect on the District School Analysis was not significant in any meaningful way.