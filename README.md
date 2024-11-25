#The interactive HR dashboard, built using Tableau

Objective
1)	Employee Data Analysis:
•	Objective: Extract and understand data related to recruitment, training, and performance levels.
•	Outcome: Enable management to make data-driven decisions regarding employees and increase operational efficiency.
2)	Process Improvement:
•	Objective: Provide data-driven strategies to improve recruitment efficiency and employee retention.
•	Outcome: Increase employee retention rates and reduce costs associated with repeated recruitment.
3)	Employee Performance Analysis:
•	Objective: Analyze performance data across different departments to identify high-performing employees and recognize patterns linked to productivity and efficiency.
•	Outcome: Improve evaluation and professional development processes, leading to overall increased productivity.
4)	Employee Turnover Prediction:
•	Objective: Use predictive analytics in Python to develop a model that forecasts the likelihood of employees leaving their jobs, identifying the factors influencing resignations.
•	Outcome: Reduce turnover rates and develop proactive strategies to retain employees.
5)	Diversity and Inclusion Analysis:
•	Objective: Evaluate employee demographic data to measure diversity within the organization and analyze inclusive patterns within teams to ensure fair representation in recruitment and promotion processes.
•	Outcome: Foster a diverse and inclusive work environment, improving performance through diversity.
6)	Training Program Evaluation:
•	Objective: Analyze training data to assess the impact of training programs on employee performance and identify the most effective programs.
•	Outcome: Improve training programs and enhance employees' professional skills.
7)	Employee Experience Improvement:
•	Objective: Analyze employee satisfaction data through surveys and key performance indicators to identify areas for improvement in the employee experience within the company.
•	Outcome: Enhance job satisfaction and increase employee loyalty to the company.
These objectives focus on improving human resource management through in-depth analysis of employee data, leading to better overall performance and more effective achievement of organizational goals.

#Dataset Used
<a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/EducationLevel.csv">Dataset</a>
<a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/Employee.csv">Dataset</a>
<a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/PerformanceRating.csv">Dataset</a>
<a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/RatingLevel.csv">Dataset</a>
<a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/SatisfiedLevel.csv">Dataset</a>


#Analysis Questions Phase
General
1.	What is the number of employees?
2.	What is the number of active employees?
3.	what is the number of attrition employees?
4.	what is the avg age?
5.	what is the Attrition Ratio?
Attrition
6.	what is the number of employees according to group age?
7.	what is the number of employees according to Education Field?
8.	what is the number of employees according to business travel?
9.	what is the number of employees according to distance?
10.	what is the number of employees according to department?
11.	what is the number of employees according gender?
12.	what is the number of employees according to state?
Job & Environmental Satisfaction
13.	what is the number of employees according to Education Field?
14.	what is the number of employees according to job role?
15.	what is the number of employees according to state?

#2)	Analysis and Forecasting Questions
In the world of data-driven decision-making, analysis and forecasting play pivotal roles. Analysis involves studying historical data to uncover patterns, trends, and insights that help businesses and organizations make informed decisions. Forecasting, on the other hand, goes a step further by predicting future outcomes based on historical data, allowing for proactive planning and strategy development.
Analysis Questions Phase
General
1.	What is the number of employees?
2.	What is the number of active employees?
3.	what is the number of attrition employees?
4.	what is the avg age?
5.	what is the Attrition Ratio?
Attrition
6.	what is the number of employees according to group age?
7.	what is the number of employees according to Education Field?
8.	what is the number of employees according to business travel?
9.	what is the number of employees according to distance?
10.	what is the number of employees according to department?
11.	what is the number of employees according gender?
12.	what is the number of employees according to state?
Job & Environmental Satisfaction
13.	what is the number of employees according to Education Field?
14.	what is the number of employees according to job role?
15.	what is the number of employees according to state?


[Main Dashboard]("D:\رواد مصر\Tableau\Main Dashboard.jpeg")
Dashboard Interaction <a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/ScreenShot.jpeg"> View Dashboaed </a> 
Dashboard Interaction <a href="https://github.com/Omda-22B/Human-Resources-Dashboard/blob/main/ScreenShot%202.jpeg"> View Dashboaed </a> 

#Key Metrics
1.	Total Employees: The dashboard reports a total headcount of 1,470 employees, giving a clear picture of the organization's workforce size.
2.	Attrition Count & Rate:
o	The attrition count stands at 237, which represents the total number of employees who have left the organization.
o	The attrition rate is 16.12%, a crucial metric for understanding employee turnover. This rate is higher than typical industry standards, suggesting that retention strategies need to be reviewed.
3.	Average Age: The average employee age is 29, reflecting a relatively young workforce. This can be an indicator of a dynamic and innovative work environment but may also signal the need for mentoring programs to ensure long-term retention and development.
Breakdown of Attrition by Department
A pie chart indicates that:
•	Technology experiences the highest attrition at 56.12%, followed by Sales at 38.82%, and Human Resources at 5.06%. This disproportionate attrition in Technology signals a potential issue with work conditions, career development opportunities, or competition in the labor market for tech talent.
Age Group and Gender Distribution
A stacked bar chart showcases the distribution of employees by age group and gender:
•	The 20-29 age group has the highest concentration of employees, almost equally divided between male and female genders.
•	A significant observation is the declining number of employees in older age groups, which may suggest challenges in retaining more experienced employees.


Job Satisfaction Rating
The Job Satisfaction Rating matrix provides valuable insight into employee contentment across various roles. A satisfaction rating scale from 1 to 5 is displayed for roles such as Analytics Manager, HR Executive, Data Scientist, and Recruiter.
•	Most roles report relatively high satisfaction, but positions like HR Executive and Engineering Manager show signs of dissatisfaction, which could be a factor contributing to attrition in these areas.
Education Field and Attrition
A bar chart presents the attrition count by education field, with notable insights:
•	Marketing and Computer Science show the highest attrition numbers at 65 and 59, respectively.
•	Employees with education in Human Resources have the lowest attrition rate at 7, suggesting that those with HR backgrounds tend to stay longer within the organization.
Gender and Age-Based Attrition Rate
The dashboard provides pie charts breaking down attrition by gender across different age groups:
•	For employees aged under 20, 60% of the attrition is female, indicating a potential gender-specific issue in this age group.
•	In the 30-39 age group, 58% of attrition is female, further suggesting that women may face unique challenges in their career progression or work-life balance within the organization.
4.	Visualization 
Data Visualization is the graphical representation of information and data. It involves creating visual elements like charts, graphs, and maps to understand large amounts of information easily and quickly. Visualization is an essential part of data analysis, as it provides an intuitive way to detect patterns, correlations, and trends in the data.

#Conclusion

This HR Analytics Dashboard offers valuable insights into workforce trends such as attrition, job satisfaction, and demographic breakdowns by gender and education. The data reveals potential areas for improvement, particularly in managing high attrition in technology departments, addressing gender-specific issues, and enhancing employee satisfaction in certain job roles. These insights are crucial for developing targeted HR strategies aimed at improving retention and employee well-being.
