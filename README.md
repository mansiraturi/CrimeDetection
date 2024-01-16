![image](https://github.com/mansiraturi/Tableau_MassEdu/assets/83804789/ec7ba06b-2e5c-4682-866f-eb638ac7f7ae)
<b> EDUCATIONAL TRENDS AND STUDENT DYNAMICS IN MASSACHUSETTS </b> <br>
<b>INTRODUCTION </b> <br>
Education is a cornerstone of societal progress, and several factors contribute to the complex landscape of student outcomes. The project delves into identifying the various aspects and patterns spread across the state of Massachusetts and studying the impact of these factors on educational disparities throughout the state. 
The data presented in this study serves as a valuable resource for decision-makers, policymakers, and educators. The insights drawn highlight disparities in resource allocation and the influence of socioeconomic factors on student outcomes. This information is instrumental in facilitating informed decision-making, improving resource allocation, planning targeted interventions, promoting educational equity, and enhancing crisis response strategies. 
PROBLEM STATEMENT
To gain a deeper understanding of the dynamics of the education system across counties, a thorough analysis of important metrics is necessary for education in Massachusetts. The questions we seek answers for are:
Q1. Do counties with higher drop-out rates have a higher population of financially weaker students?
Q2. Does class size affect the probability of students attending colleges or universities?
Q3. Are financially weaker students more likely to not attend classes?
Q4. How did the pandemic affect the education institution choices in Massachusetts? 
DATA DESCRIPTION
For the project, 6 datasets were used for analysis and visualization. The Massachusetts state report provided data for the student- teacher ratio, dropout rates per county, the choice of schooling preferred by students and the choice of higher education. For a few representations, data was collected from 2017 to 2022. Each dataset had county-wise data with distinctive features as described above
METHODOLOGY:
1.	Data Collection:
·	Gathered a diverse dataset from various educational institutions.
·	Ensured inclusivity of student demographics, academic performance metrics, teacher details, suspension records, dropout rates, and financial conditions.
2.	Data Cleaning and Preprocessing:
·	Eliminated missing or incomplete data to enhance accuracy.
·	Standardized variables for consistency in measurements and included calculated fields to establish relationships
·	Converted categorical variables to numerical formats along with merging datasets to draw comparison.
3.	 Quantitative Analysis:
·	Calculated student-to-teacher ratios for each county and categorized ratios. 
·	Conducted correlation analyses to identify relationships between student-to-teacher ratios and suspension rates.
·	Adding relevant dimensions and measures to the sheet in tableau and defining functions based on the visualizations. 
4.	Visualization Techniques:
·	Utilized visualizations to effectively communicate complex trends.
·	Developed a timeline visualization depicting the underlying patterns during the pandemic 
·	Added filters to draw interpretations based on user requirements and choice of data. 
·	Compiled all visualizations in a dashboard 

SKETCHBOARD
  

KEY INSIGHTS FROM THE DATA
1)	Relation between dropout students and economic disadvantage
Inference:
The average student-teacher ratio is 15.7. This is a low ratio compared to other states in the US as the national average student-teacher ratio is 16.8.
There is a significant variation in the student-teacher ratio across schools: The lowest ratio is 8.7, while the highest is 28.7. Private schools tend to have lower student-teacher ratios: The average student-teacher ratio in private schools is 13.6, compared to 16.1 in public schools.
Charter schools have a wider range of student-teacher ratios while urban schools tend to have higher student-teacher ratios. 
Hypothesis:
The variation in the ratio suggests that some schools have significantly more resources than others. 
This may be because urban schools often have more students from low-income families, who may need more support. 
These insights can be used to inform policy decisions about how to allocate resources and improve educational outcomes for all students in Massachusetts like providing additional funding to schools with high student-teacher ratios, particularly in urban areas. They may also want to invest in programs that help private and charter schools maintain their low student-teacher ratios. This suggests that some schools have significantly more resources than others.

2)	Class size and graduation percentage
Inference: 
The statistical analysis reveals a significant relationship between the percentage of students attending college or university and the natural logarithm of average class size. The regression equation, Attending Coll./Univ. (%) = 24.7648 * ln(Average Class Size) - 11.4679, indicates that as the natural logarithm of class size increases, there is an associated positive change in the percentage of students attending higher education institutions. The p-value of < 0.0001 for the coefficient of ln(Average Class Size) underscores the statistical significance of this relationship. However, the intercept's p-value of 0.447247 indicates it may not be statistically significant. This analysis provides valuable insights into the impact of class size on educational outcomes.
Hypothesis:
The analysis suggests that in Massachusetts schools, increasing class sizes might positively impact the percentage of students attending college. The initial college attendance may not be significantly influenced by class size alone, as indicated by a non-significant intercept p-value. It can be hypothesized that presence of more students leads to more interaction among students which encourages students to apply for colleges and pursue further education
3)	Relation between economically disadvantaged students and their attendance. 
Inference:
 The scatter plot depicts a correlation between the average attendance rate per county and the financial status of the students. A clear increase in the absence rate can be observed with the increase in the proportion of weaker financial status among the population. 
Hypothesis:
From this, an assumption can be made that students with a weak financial background tend to miss classes and not go to school. This could be because they are busy making ends meet by working and hence don’t get much time for classes and schoolwork. It could also be assumed that they lack financial resources for other school-related expenses and therefore don’t see any motive behind attending school. 
4)	The proportion of students homeschooled 
Inference:
The visual representation depicts and contrasts the proportion of students across the state of Massachusetts attending private or public school or are home schooled. The visualization clearly highlights the hike in home schooling from 2020, which coincides with the start of the pandemic (COVID-19). The difference in pre covid and the post covid time can be observed and hence leading to such a conclusion. From this it can be assumed that parents and students preferred homeschooling more as they found it safer and a more convenient option. 
Hypothesis:
The peak was observed during the pandemic, however, even after the pandemic, homeschooling remained a popular choice among students. This suggests a correlation between economic conditions, exacerbated by the pandemic, and educational choices
REFERENCES:
1]  https://profiles.doe.mass.edu/statereport/classsizebygenderpopulation.aspx <br>
2] https://profiles.doe.mass.edu/statereport/schoolattendingchildren.aspx <br>
3] https://profiles.doe.mass.edu/statereport/dropout.aspx <br>
4] https://profiles.doe.mass.edu/statereport/attendance.aspx  <br>
5] https://profiles.doe.mass.edu/statereport/ssdr.aspx <br>
6] https://profiles.doe.mass.edu/statereport/ssdr.aspx <br>




  

