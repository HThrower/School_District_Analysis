# School_District_Analysis
Analysis of School and Student data using the Pandas Library and the Jupyter Notebook.

This is analysis is focused on understanding how a variety of schools compare to one another on the basis of total budget, budget per pupil, and test scores across reading and math. The analysis further segments schools down by size and type (charter or public). The analysis will be presented to the school board for education. A variant of the analysis has a grade from a high school removed due to a suspected fraudulent activity.

## Results:

How is the district summary affected?
![image](https://user-images.githubusercontent.com/31675832/137650986-49390b38-fb6e-40f5-a428-2d1442820b5f.png)

![image](https://user-images.githubusercontent.com/31675832/137649282-09b86f2e-f0e8-481a-83ee-3bd165fed0d6.png)

high and low performing school

![image](https://user-images.githubusercontent.com/31675832/137649961-319cf2b7-a51c-4034-9d1e-fafac00aa401.png)

Math and reading scores by grade

How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:

Scores by school spending
![image](https://user-images.githubusercontent.com/31675832/137650930-16eb1814-726c-4765-bae3-fdb89946d691.png)

Scores by school size
![image](https://user-images.githubusercontent.com/31675832/137650868-0d257534-041f-4c91-a707-ef8d06e74704.png)

Scores by school type
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.



*Average math and reading scores stay consistent across grade level when grouped by school. There is no major improvement in scores from any school.
Math passing rates are always consistently lower across every metric, but the difference between math and reading passing rates is greater amoung lower performing schools, large schools, and higher spending per student which all seem to correlate.
*The top 5 schools are all charter schools while the bottom 5 all district schools.
*In general (one exception), per student spending is higher in bottom performing schools than top performing.
Schools under 2000 students have much higher passing rates than those with student populations above 2000. A comparision of 95 to 75%. The same phenomenon is seen with high and low per student spending brackets and district versus charter schools.
