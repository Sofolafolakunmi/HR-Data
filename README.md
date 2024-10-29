#### HR-Data

#### PROJECT OVERVIEW
This analysis investigates the drivers of employee attrition in an organization using a dataset comprising demographic information, job-related attributes, and satisfaction measures. Key objectives include identifying trends and patterns associated with attrition, understanding the role of job satisfaction, compensation, and career progression in influencing employee decisions to leave, and developing a predictive model to forecast attrition. The findings of this analysis will support data-driven decisions for employee retention, ultimately helping the organization reduce turnover costs and build a more committed workforce. We can also gain insights into the dynamics that lead to employee attrition, which will help the organization improve retention strategies and enhance employee engagement.
Employee attrition is a significant concern for organizations as it leads to high costs associated with recruitment, training, and loss of productivity. Understanding the factors that contribute to employee turnover is essential for developing effective retention strategies. This study aims to identify key predictors of attrition within an organization by analyzing demographic, job-related, and satisfaction metrics.

#### Columns Explanation
-	Attrition: Indicates whether an employee has left the company (often represented as "Yes" or "No").
-	Business Travel: Frequency of business travel for the employee (e.g., "Rarely," "Frequently," "No Travel").
-	CF_age band: Age group category of the employee, often used to group ages into ranges (e.g., "20-30," "30-40").
-		CF_attrition label: Custom attrition label for categorizing employees based on attrition (could be a grouping of reasons or types of attrition).
-		Department: Department where the employee works (e.g., "Sales," "Engineering," "HR")
-		Education Field: Field of study of the employee’s highest education (e.g., "Engineering," "Human Resources").
-		Employee Number: Unique identifier for each employee.
-		Gender: Gender of the employee (e.g., "Male," "Female").
-		Job Role: The specific job title or role of the employee within the organization (e.g., "Manager," "Sales Representative").
-	  Marital Status: Marital status of the employee (e.g., "Single," "Married").
-	  Over Time: Indicates if the employee works overtime (e.g., "Yes" or "No").
-	  Over18: Indicates if the employee is over 18 (may not be very insightful if everyone is above this age).
-	  Training Times Last Year: Number of times the employee received training in the previous year.
-	  Age: Employee’s age.
-	  CF_current Employee: Likely a custom field indicating whether the employee is currently employed (often "Yes" or "No").
-	  Daily Rate: Daily wage of the employee (could be in dollars or any other currency).
-	  Distance From Home: Distance between the employee’s home and workplace (usually in miles or kilometers).
-	  Education: Education level of the employee, often represented as a number (e.g., 1 = Below College, 2 = College, 3 = Bachelor, 4 = Master, 5 = Doctorate).
-	  Employee Count: Typically the count of employees per row; this may always be 1 if each row represents a single employee.
-	  Environment Satisfaction: Employee’s satisfaction with the work environment (usually on a scale, e.g., 1 = Low, 2 = Medium, 3 = High, 4 = Very High).
-	  Hourly Rate: Employee’s hourly wage.
-	  Job Involvement: Employee’s involvement in their job (often on a scale, e.g., 1 = Low, 2 = Medium, 3 = High, 4 = Very High).
-	  Job Level: The level or rank of the job within the organization (e.g., 1 = Entry, 2 = Mid, 3 = Senior).
-	  Job Satisfaction: Satisfaction level of the employee with their job (e.g., 1 = Low, 2 = Medium, 3 = High, 4 = Very High).
-	  Monthly Income: Employee’s monthly income.
-	  Monthly Rate: The monthly rate of pay, potentially used in salary calculations.
-	  Num Companies Worked: Number of companies the employee has worked for, which may indicate experience or stability.
-	  Percent Salary Hike: The percentage increase in salary from the previous year.
-	  Performance Rating: Performance rating of the employee (e.g., 1 = Low, 2 = Good, 3 = Excellent, 4 = Outstanding).
-	  Relationship Satisfaction: Satisfaction level with personal relationships at work (e.g., 1 = Low, 2 = Medium, 3 = High, 4 = Very High).
-	  Standard Hours: The standard working hours for an employee, often 40 hours per week.
-	  Stock Option Level: Level of stock options granted to the employee (e.g., 0 = No stock options, 1 = Low, 2 = Medium, 3 = High).
-	  Total Working Years: Total years of work experience the employee has had.
-	  Work Life Balance: Work-life balance satisfaction, often on a scale (e.g., 1 = very dissatisfaction, 2 = dissatisfaction, 3 = satisfaction, 4 = very  satisfaction).
-	  Years At Company: Number of years the employee has been with the company.
-	  Years In Current Role: Number of years the employee has held their current role.
-	  Years Since Last Promotion: Number of years since the employee’s last promotion.
-	  Years With Current Manager: Number of years the employee has worked with their current manager.
  
#### Data Source
The main data sources for this analysis is from the HR of an organization. It’s also “HR.Data.csv” file. 

#### Tools Used
Power BI: Used for both data cleaning and visualization


#### Methodology (Data Cleaning and Preparation)
### Data Cleaning
The data cleaning process was performed in Power BI, following these steps:
## Column Renaming: Renamed columns for improved clarity and consistency.
## New Column Creation:
i.  Used a conditional column to classify age brackets (Age_Band).
ii. Created a rating for job satisfaction.

#### Exploratory Data Analysis (EDA)
The data was imported from Excel into Power BI, and the following steps were conducted:
i.   Descriptive Statistics: Calculated attrition rate and average age.
ii.  Visualization: Developed maps, cards, and charts to identify trends, patterns, and gain insights.
iii. Dashboard Creation: Built an interactive dashboard to effectively present key findings.

#### Statistic Analysis 
The total number of employees is 1470 
Total number of attritions is 237 
Total number of current employees is 1233 
Average age is 37 
Attrition rate is 16%  
 
 #### Result
- Attrition by Department:
i.   Attrition appears to vary significantly by department:
ii.  The R&D department has the highest attrition with 961 employees leaving.
iii. Sales follows with 446 employees leaving.
	The HR department has the lowest attrition at 63 employees.
- Attrition by Education Field:
i.  The Life Sciences field has the highest attrition count, followed by Medical and Marketing.
ii. Fields like Technical Degree and other specialties show relatively lower attrition.
- Attrition by Gender:
i.A majority of the attrition (63.29%) is from male employees (150), while females account for 36.71% (87) of attrition cases.
- Attrition by Gender and Age Band:
i. The age and gender breakdown shows:
ii. 122 employees in 25-34 age band and gender has the highest attrition 
iii. Suggesting different age bands have distinct attrition patterns when combined 

#### Recommendations 
- Focus on Retention in High-Attrition Departments:
i. Since the R&D and Sales departments have the highest attrition rates, it may be beneficial to conduct exit interviews or surveys to understand the specific reasons why employees in these departments are leaving.
ii. Based on these insights, consider implementing targeted retention strategies, such as career development programs, performance incentives, or work-life balance initiatives, to reduce turnover in these departments.
- Enhance Support for Life Sciences and Medical Education Fields:
i. Given that employees with backgrounds in Life Sciences and Medical fields show higher attrition, consider establishing specialized career growth paths, training programs, or mentorship opportunities to increase engagement and job satisfaction within these groups.
ii. Understanding the skill development needs and career goals of these employees could help improve retention in these fields.
- Address Gender-Specific Retention Challenges:
i. Since attrition is higher among male employees, investigate potential reasons for this trend, such as job satisfaction, work environment, or career advancement concerns that may disproportionately affect men.
ii. Ensure that both male and female employees feel equally supported and valued by providing flexible policies, growth opportunities, and a healthy work-life balance.
- Targeted Retention Efforts for Specific Age Bands:
i. With higher attrition rates in certain age and gender combinations, consider tailoring retention efforts for different age groups. Younger employees may value opportunities for skill-building and career advancement, while older employees may prioritize job security and work-life balance.
ii. Tailored retention initiatives based on age demographics could help in addressing the unique needs of each group and reduce attrition.
- Develop an Inclusive and Supportive Workplace Culture:
i. Since attrition can often be influenced by workplace culture, consider fostering a supportive and inclusive environment through regular employee engagement activities, team-building exercises, and transparent communication.
ii. Providing a positive workplace culture can significantly impact overall employee satisfaction and may lead to lower attrition rates

