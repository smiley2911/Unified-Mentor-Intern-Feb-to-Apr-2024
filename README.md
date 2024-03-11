# Unified Mentor Intern
## Project Title - Employee Attrition Analysis

❇️ Python - [Insights](https://github.com/arun10ak/Unified-Mentor-Intern/blob/main/Employee%20Attrition.ipynb)

❇️ Novypro Power BI Dashboard - [Live Report Link](https://www.novypro.com/project/employee-attrition-analysis-10)

### Project Objective :
---
![greendestination+logo](https://github.com/arun10ak/Unified-Mentor-Intern/assets/117892039/a8eb0286-4b8e-4d08-8d3a-e0231db077cb)

Green Destinations is a well-known travel agency. The HR Director has recently noticed an increase in employees leaving (attrition). She would like to figure out any trends or patterns. She has surveyed the staff of Green Destinations and provided you with the data. She would like to know what the attrition rate is (% of people who have left). She would also like to know if factors like age, years at the company, and income play a part in determining if people will leave or not.

### Data Source : 
---

we used csv [file](https://github.com/arun10ak/Unified-Mentor-Intern/blob/main/greendestination.csv) . It contains the  details of the employees of the company.

 **'Age','Attrition', 'BusinessTravel', 'DailyRate', 'Department','DistanceFromHome', 'Education', 'EducationField', 'EmployeeCount',**
 
**'EmployeeNumber', 'EnvironmentSatisfaction', 'Gender', 'HourlyRate','JobInvolvement', 'JobLevel', 'JobRole', 'JobSatisfaction',**

**'MaritalStatus', 'MonthlyIncome', 'MonthlyRate', 'NumCompaniesWorked','Over18', 'OverTime', 'PercentSalaryHike', 'PerformanceRating',**

**'RelationshipSatisfaction', 'StandardHours', 'StockOptionLevel','TotalWorkingYears', 'TrainingTimesLastYear', 'WorkLifeBalance',**

**'YearsAtCompany', 'YearsInCurrentRole', 'YearsSinceLastPromotion','YearsWithCurrManager'**

### Tools Used :
---

- MS Excel
- Python
- Power BI

### Power BI :
---

#### Data Preparation
- Import your employee dataset into Power BI.
- Ensure that the dataset includes relevant fields such as employee ID, hire date, termination date (if applicable), performance ratings, department, etc.
- Cleanse and transform the data as needed, handling missing values and ensuring consistency.

#### Design the dashboard layout based on the insights you want to derive.

Include visuals such as charts, graphs, and tables to represent key metrics related to employee attrition.

**Examples of visuals to include:**

1. Attrition Rate Over Time: Line chart showing the trend of attrition over time.
2. Attrition by Department: Bar chart illustrating attrition rates by department.
3. Reasons for Attrition: Pie chart or stacked bar chart showing reasons for employee attrition (e.g., voluntary resignation, termination, retirement).
4. Employee Tenure Distribution: Histogram showing the distribution of employee tenure within the organization.
5. Attrition Prediction (Optional): Utilize machine learning algorithms (if applicable) to predict future attrition based on historical data. Display the predicted attrition rates alongside actual rates.

### Dashboard :
----
![image](https://github.com/arun10ak/Unified-Mentor-Intern/assets/117892039/30732fba-5811-4a6e-b413-08e636e315e5)

#### Key Insights :

1. **Age**: Uncover attrition patterns by age groups. Most attrition occurs in the 26-35 age group.

2. **Salary**: Analyze attrition relative to salary bands. The highest attrition is seen in employees earning up to 5K.

3. **Years of Service**: Spot trends based on employee tenure. Attrition spikes after one year with the company.

4. **Education**: Explore attrition data by educational background. Life Sciences Education has a 38% attrition rate.

5. **Job Role**: Discover which roles face higher attrition. Laboratory technicians have the highest attrition rate at 62%.

6. **Gender**: Compare attrition rates between genders. It's higher for males compared to females.

7. **Job Satisfaction**: Attrition is linked to job satisfaction across roles. Lower satisfaction means higher attrition risk.

### Python 
---

1. Data Collection and Preparation
- Collect historical employee data from relevant sources such as HR databases or CSV files.
- Preprocess the data to handle missing values, outliers, and inconsistencies.
- Split the dataset into training and testing sets.
  
2. Exploratory Data Analysis (EDA)
- Explore the dataset to understand the distribution and relationships of variables.
- Visualize key features to identify patterns and correlations.
- Conduct statistical analysis to gain insights into factors influencing employee attrition.
  
3. Feature Engineering
- Engineer new features or transform existing ones to improve model performance.
- Encode categorical variables using techniques such as one-hot encoding or label encoding.
- Scale numerical features to ensure uniformity across different ranges.

4. Model Training
- Train the random forest model using the training dataset.
- Fine-tune model hyperparameters using techniques such as grid search or random search to optimize performance.
- 
5. Model Evaluation
- Evaluate the trained models using the testing dataset.
- Measure performance metrics such as accuracy.
-  Use confusion matrices and ROC curves to visualize model performance.
-  
7. Model Interpretation
- Interpret the trained models to understand the importance of features in predicting employee attrition.
- Identify key drivers contributing to attrition and their impact on the prediction.

#### Key Insights :

1. Attrition Rate:
- About 16.12% of employees leave the company.
- Factors Contributing to Attrition:

2. Attrition is higher in the Research & Development department.
- Employees with backgrounds in Life Sciences and Technical Degrees tend to leave more.
- Many employees leave after one year, possibly due to retention issues.
- Employees without recent promotions are more likely to leave.
- Men tend to leave more than women.
- Lower-income employees are more likely to leave.
- Relationship between Age, Monthly Income, and Attrition:

3. Older employees generally have higher incomes.
- Those with lower incomes are more likely to leave.

4. Correlation Analysis:
- Overtime, marital status, distance from home, job role, and department are positively correlated with attrition.
- Satisfaction-related factors are negatively correlated.

5.Employee Attrition Prediction:
- A model predicts attrition with 86.39% accuracy.

