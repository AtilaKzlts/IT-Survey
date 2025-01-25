![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/8.png)
# | Information Technologies Survey Analysis

### Table of Contents

- Project Introduction
    - Executive summary
    - About the Data Set
    - Objective
- Analysis Outputs
- Detailed Summary

## Project Introduction

2020 IT Industry Survey: Examining demographics, salary trends, and workplace dynamics among technology professionals, we used Multidimensional Category Analysis (MCA) to delve deeper into the latent relationships and interactions between categorical variables. The findings reveal key parameters such as gender distribution, age demographics, and salary differences between different positions, as well as complex linkages between variables, providing industry insights.”

## Executive summary

The most common position of the mostly male employees is software engineer, and they are concentrated in large cities (especially Berlin and Munich). They are usually in senior positions and the most popular technologies are Python and Java. In addition, the majority of employees work full-time, with more vacation days in larger companies. Salary and vacation days increase as experience increases.
Male employees are usually located in Berlin and in senior positions, while female employees are in the younger age group and speak English as their first language. Full-time work is more common in large companies, while freelancers are more common in small firms and startups. There are also clear relationships between positions and technologies: Data Scientist and Python, Backend Developer and Java/SQL, Frontend Developer and JavaScript/TypeScript.

## About the Data Set

| Column Name                        | Description                                      |
|-------------------------------------|--------------------------------------------------|
| ``Date``                            | Timestamp of the survey entry                    |
| ``Age``                             | Age of the respondent                            |
| ``Gender``                          | Gender of the respondent                         |
| ``City``                            | City of the respondent                           |
| ``Position``                        | Job position of the respondent                   |
| ``TotalExp``                        | Total work experience                            |
| ``ExpInGermany``                    | Experience specifically in Germany               |
| ``Seniority``                       | Seniority level                                  |
| ``MainTech``                        | Primary technology used                          |
| ``OtherTech``                       | Additional technologies used                     |
| ``Yearly brutto salary``            | Annual gross salary in EUR                       |
| ``Yearly bonus + stocks in EUR``    | Annual bonus and stock compensation              |
| ``VacationDays``                    | Number of vacation days                          |
| ``EmploymentStatus``                | Current employment status                        |
| ``Сontract duration``               | Length of employment contract                    |
| ``MainLanguage``                    | Primary work language                            |
| ``CompanySize``                     | Size of the company                              |
| ``CompanyType``                     | Type of company                                  |
| ``LostJobDueToCOVID``               | Job loss status during COVID-19                  |
| ``WFHSupportAmount``                | Work-from-home support amount                    |
| ``Month``                           | Month of the survey entry                        |
| ``age_group``                       | Categorized age group                            |

## Objective

Demographic Distribution Analysis:
+ Analyzing the distribution of IT professionals by age, gender and other demographic characteristics.

Identifying Salary Trends:
+ Analyzing salary differences between different positions, age groups and genders to reveal salary dynamics across the industry.

Analyzing Relationships between Categorical Variables:
+ To identify hidden relationships and interactions between categorical variables using Multidimensional Category Analysis (MCA).


## Analysis Outputs

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/1.png)

In terms of employee distribution, there are 600 male employees and 200 female employees. The largest location is Munich, followed by Berlin and Frankfurt. Positions are dominated by software engineering, with the highest number of employees in senior roles, followed by leadership, mid-level and junior roles. Programming languages include C++ and PHP, while Python and Java are also widely used. Employment is mostly full-time, with contracts usually for an indefinite period. English, German and Russian are the main languages used, while company sizes are mostly small.

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/2.png)

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/3.png)
In terms of age distribution, the 30-35 age range is dominant. The distribution of total work experience reaches high levels around 10 years.
In terms of work experience in Germany, there is a concentration in the range up to 5 years. Annual gross salary is around €60,000, while annual bonuses and share payments are most common around €10,000.
The distribution of vacation days has a clear peak around 30 days. This indicates a standard vacation policy.
The highest WFH support is EUR 1,000 and the 4th month stands out in the monthly distribution. Within the age groups, employees in the 30-39 age group are the most dominant.


![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/4.png)
In the top panel, the software engineer position has the widest salary distribution, with gross annual salaries ranging from 25,000 to 175,000. Senior and leader positions are at the top of the salary levels, while intern and student level salaries are lower. In addition, salaries for positions such as DevOps, data scientist and machine learning engineer increase significantly with increasing seniority. In the bottom panel, annual leave days are analyzed according to company size. In large companies (1,000+ employees), annual leave is generally concentrated between 25-30 days, while in small companies (up to 10 employees), a wider distribution and fewer days of leave are noteworthy. As experience levels increase, annual leave days generally increase.



![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/5.png)

Proximity Relationship:
There are strong relationships between nearby points. For example, the categories Gender_Male, City_Munich and Seniority_Senior are related.
Distant points show weak relationships or unique characteristics.

Clusters and Quartiles:
Bottom left quadrant: Male respondents are associated with Berlin and senior positions.
Bottom right quadrant: Female respondents are associated with 20-29 age group and English as first language.
Upper right quadrant: Categories such as Gender_Diverse exhibit more distant, unique characteristics.

Language and Age Relationships:
English speakers are generally in younger age groups, while German and Russian languages are divided into more distinct clusters.



![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/6.png)
Proximity Relationship: Close points represent strong relationships. For example, the categories CompanyType_Product, CompanySize_1000+ and EmploymentStatus_Full-time employee are related.
Distant dots indicate weak relationships or unique features.

Clusters and Quartets:
Bottom left quadrant: Small firms (CompanySize_11-50) and CompanyType_Startup are related.
Bottom right quadrant: Self-employed and part-time workers are associated with startup companies.
Upper right quadrant: Categories such as Contract duration_Other exhibit unique and rare characteristics.

Company and Labor Relations:
While full-time work is common in large companies, freelancers and part-timers are more common in startups.


![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/7.png)
Proximity Relationship:
Close points represent strong relationships. For example, the categories Position_Data Scientist and MainTech_Python are related.
Distant dots indicate weak relationships or unique features.

Clusters and Quartets:
Top left quadrant: Data scientists and Python-oriented workers.

Bottom right quadrant: Software engineers, associated with technologies such as Java and PHP.
Upper right quadrant: Frontend developers are associated with Javascript/Typescript technologies.

Technology and Position Relationships:
Backend development positions usually work with Java and SQL, whereas Frontend positions tend to work with Javascript/Typescript.

## Detailed Summary


### **Categorical Features** +

+ **Gender Distribution** :
The majority of the IT sector employees surveyed are men. There are more than 700 male employees, about 150 female employees and very few people belonging to the ‘other’ gender category.

+ **City Distribution**:
The cities with the highest concentration of employees are Berlin and Munich. There are around 350 employees in Berlin

+ **Position Distribution**:
The most common position is Software Engineer, with more than 250 employees. This is followed by Backend Developer and Data Scientist positions. 

+ **Seniority Level Distribution**:
The majority of the participants are at senior level. More than 300 employees work in senior positions, demonstrating the high demand for experienced professionals in the IT sector.

+ **Main Technology Breakdown**
Among the respondents, Python and Java are the most common mainstream technology languages. They are preferred by about 100 employees each, indicating that these languages are dominant in the IT sector. 

+ **Other Technologies Distribution**
JavaScript/TypeScript and SQL stand out among other technologies. 

+ **Employment Status Distribution**
Most of the respondents are full-time employees. More than 800 people work full-time, indicating that job security in the sector is high and full-time employment is the most common working pattern.

+ **Mother Language Distribution**
English is by far the most widely used native language in the IT industry. 

+ **Company Size Distribution**
Employees are concentrated both in companies with 51-100 employees and in large-scale companies with more than 1000 employees. This indicates that medium-sized and large-sized companies have an important place in the IT sector, while small-sized companies are less common.

+ **Company Type Distribution**
Product-based companies (Product) are the most common type of employer. Around 500 people work in such companies, indicating that product development and innovation are at the forefront of the sector.


### **Numerical Features** +
+ **Age Distribution:** It shows that most of the employees working in the IT sector are young or middle-aged.

+ **Total Experience Distribution:** There is a marked diversity among the experience levels of employees. This shows that both experienced and newly graduated employees are in the sector.

+ **Annual Gross Salary:** The salary distribution shows a skewed distribution to the right. This shows that there is a minority with high salaries and a majority with lower salaries in the sector.

+ **Holiday Days:** The average number of holidays per year for employees is mostly between 28-30 30+ holidays are very rare

+ **Remote Working Support** 475-500 Euro                 


### **Multivariant analysis** + 
**Annual Gross Salary Breakdown by Position**

This graph shows how the annual gross salaries of employees in different positions are distributed.

+ Position and Salary Relationship: In general, employees in more senior positions (Senior, Lead, Principal) have higher salaries. This shows that the salary increases with the increase in experience and responsibility.
Salary Differences within Positions: It is observed that there are significant differences between the salaries of people working in the same position. These differences may arise from factors such as company size, department, performance evaluations or location.

**Distribution of Holiday Days by Company Size and Experience Level**

This graph shows the average annual holiday days of employees in different company sizes and with different levels of experience. 

+ Company Size and Holiday: In general, employees in larger companies have more holiday days.

+ Experience Level and Holiday: It is observed that as the experience level increases, the number of holiday days also increases.


### **MCA Analysis**

Proximity and Relationships:
+ Categories with the same or similar characteristics are located close to each other in the charts. For example, the Data Scientist position and Python core technology show a strong relationship, while the Frontend Developer position and JavaScript/TypeScript technology are also linked.
More distantly located categories have unique characteristics that differentiate them from other categories in the dataset. For example, categories such as OtherTech_Kotlin and Gender_Diverse may be less representative in the dataset or exhibit different characteristics.

Positions and Technologies:
+ There is a strong correlation between Backend Developer and technologies such as Java, PHP, SQL. This emphasizes that these technologies are fundamental in backend roles.
The Data Scientist position is particularly associated with Python. It reflects the popularity and use of Python in data science.
The Frontend Developer position is associated with JavaScript/TypeScript, highlighting the critical importance of these technologies in user interface development.

Cities and Seniority:
+ Berlin and Munich stand out as cities where senior employees are concentrated.
Those working in smaller or more remote cities can often be associated with different positions and technologies.

Language and Age:
+ English speakers are more often associated with younger age groups.
German and other languages may be associated with employees in different age groups and positions.                             
