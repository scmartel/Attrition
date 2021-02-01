# Attrition
End-to-end machine learning project completed for academic purposes. The aim of this project is to predict the monthly salaries of employees of the synthetic IBM HR analytics employee attrition and performance dataset

The objective of the current synthetic dataset was to uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists.

For the purpose of this project, a continuous variable was predicted (monthly salary) using valid predictors available from the Attrition dataset. 

### Data Description ###
* Age; Age of employee
* Attrition; (Yes/No) Whether an employee retire/resigns
* BusinessTravel; Frequency of business travel
* DailyRate: Daily rates of production
* Department: Company department
* DistanceFromHome: Distance from the employees home
* Education: Education level
* Education field: Education speciality (ie life sciencecs, medical, technical etc)
* Employee Count: Unary (to drop)
* Employee Number: Employee ID
* Environemnt satisfaction: Likert value for work environment satisfaction
* Gender: Male/Female
* HourlyRate: Hourly rate of salary
* JobInvolvement: Levels of job involvement (low, medium, high, very high)
* JobLevel: Levels of job in company (1,2,3,4)
* JobRole: Job title
* JobSatisfaction: Likert scale of job satisfaction
* MaritalStatus: Single/Married/Divorced
* MonthlyIncome: TARGET variable
* MonthlyRate: unknown description - to be dropped
* NumberCompaniesWorked: Number of companies worked in the past
* Over 18: Y/N
* OverTime: Yes/No
* PercentSalaryHike: Increase in salary since start
* PerformanceRating: Scale of rating of performance (low, good, excellent, outstanding)
* RelationshipSatisfaction: Low, medium, high, very high
* StandardHours: Unary - to drop
* TotalWorkingYears: Total working years
* TrainningTime: Total training time
* WorkLifeExperience: Categorical values of worklife experience
* YearsAtCompany: Years spent working at company
* YearsinCurrPosition: Years spent in current position
* YearsSinceLastPromotion: Years since the last promotion
* YearsWithCurrManager: Years with current manager

 ### Description of categorical variables ### 

* Education : (1: 'Below College',2: 'College', 3: 'Bachelor', 4: 'Master', 5: 'Doctor')
* EnvironmentSatisfaction: (1: 'Low', 2: 'Medium', 3: 'High', 4: 'Very High')
* JobInvolvement: (1: 'Low', 2: 'Medium',3: 'High', 4: 'Very High')
* JobSatisfaction: (1: 'Low', 2: 'Medium',3: 'High', 4: 'Very High')
* PerformanceRating: (1: 'Low', 2: 'Good', 3: 'Excellent', 4: 'Outstanding')
* RelationshipSatisfaction: (1: 'Low', 2: 'Medium', 3: 'High', 4: 'Very High')
* WorkLifeBalance: (1: 'Bad', 2: 'Good', 3: 'Better', 4: 'Best')


Reference: https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset
