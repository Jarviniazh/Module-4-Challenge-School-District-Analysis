# School District Analysis

## Project Overview 

### Purpose
We will help the chief data scientist for a city school district analyze data on student funding and student’s math and reading scores as well as various information on the school they attend. Our task is to aggregate the data and showcase trends in school performance. However, the dataset especially Thomas High School ninth graders show evidence academic dishonesty that we need to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact first. This analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

## School District Analysis Results
Due to potential academic dishonesty by the 9th-grade students from Thomas High School, we ran the analysis twice to figure out the impact of this issue. The first round of this analysis included the whole dataset, while in the second trial, we omitted the Thomas High School ninth graders’ math and reading scores omitted from the calculations. After replacing the inaccurate data for the 9th graders at Thomas High School, there are some changes occurred.
- District summary: The overall differences are too small to notice after replacing. Only the average math score decrease 0.2 and there are not any changes between average reading score. All passing percentages have slightly drop around 0.2%-0.3%.  
- School summary: Thomas High School is affected by this replacing. All score related data are differed from the original one, and only the average math score shows a better result with 0.05 increase. The others face slightly decrease, and the overall passing percentage has the largest change which shrink 0.32% but still within the 90 percentile passing.  
- Thomas High School's performance v.s. the other schools: Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
- Other factors:
  -  Math and reading scores by grades: only the average math and reading score of Thomas High School ninth graders are replacing from 83.6 and 83.7 to NaN. All the other scores are not affected by the replacing.
  -  Scores by school spending: There is not any changes
  -  Scores by school size: The passing reading percentages are significantly increased, specially the small and medium size school have over 10 points improvement. However, the other factors are not changed.
  -  Scores by school type: There is not any changes 

## School District Analysis Summary
Though 461 9th-grade students from Thomas High School is minimal compared to a total of 39,170 students, the replacing might still impact the analysis results from the following four ponits.
1. The overall performance of Thomas High School is heavily affected without no doubt. Comparing with the top one school, Cabrera High School, before revised the data, the gap of the two schools’ overall passing percentage is only about 0.4%, but now the difference enlarges to 0.7%, almost doubled. And even worse, the gap between third school and Thomas High School now narrows down to only 0.03%.    
2. Without Thomas High School ninth grader, the overall performance of this district is also affected, since the overall passing percentage of Thomas High School dropped and the other school stayed same, the updated number of overall passing percentage for the whole district shrink to 64.9%.
3. Considering Thomas High School has the highest budget for each student among the top five schools, but with the updated analysis Griffin High School may surpass second place in the future. Therefore, the board of Thomas High School may consider the return on investment for following academic year.
4. When we omitted Thomas High School ninth graders from analysis, the updated average reading pass percent for all size increased a lot. But when it comes to the overall passing percentage or the school types, there is not significant change which school board and superintendent should focus on.    

