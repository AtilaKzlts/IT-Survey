![image](https://github.com/AtilaKzlts/Finance-Application-Complaints/blob/main/assets/pics/bar.png)

<div align="center">
  <h1>Information Technologies Survey Analysis</h1>
 </p>
</div>

## Table of Contents

- **Project Introduction**  
  - Executive Summary  
  - About the Data Set  
  - Objective  
- **Analysis Outputs**  
- **Detailed Summary**  

## Project Introduction

This analysis is based on the **2020 IT Industry Survey**, which examines demographics, salary trends, and workplace dynamics among technology professionals. We applied **Multidimensional Category Analysis (MCA)** to explore latent relationships and interactions between categorical variables. The findings provide insights into key parameters such as **gender distribution, age demographics, salary variations across different roles, and the interconnections between various factors** within the industry.

[See the notebook](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/notebook/it_survey.ipynb)

## Executive Summary

- The **most common position** among employees, predominantly male, is **Software Engineer**, with most professionals concentrated in large cities, especially **Berlin and Munich**.
- Senior positions are prevalent, and **Python and Java** are the most widely used technologies.
- The majority of employees work **full-time**, and vacation days tend to be higher in larger companies.
- **Salary and vacation days** increase with experience.
- **Male employees** are more frequently in **Berlin and senior roles**, while **female employees** are younger and tend to have **English as their primary language**.
- Full-time employment is more common in large companies, whereas freelancers are more frequently found in startups.
- Strong correlations exist between **job positions and technologies**:
  - **Data Scientists** primarily use **Python**.
  - **Backend Developers** frequently use **Java and SQL**.
  - **Frontend Developers** work mainly with **JavaScript and TypeScript**.

## About the Data Set

| Column Name                        | Description                                      |
|-------------------------------------|--------------------------------------------------|
| `Date`                              | Timestamp of the survey entry                    |
| `Age`                               | Age of the respondent                            |
| `Gender`                            | Gender of the respondent                         |
| `City`                              | City of the respondent                           |
| `Position`                          | Job position of the respondent                   |
| `TotalExp`                          | Total work experience                            |
| `ExpInGermany`                      | Experience specifically in Germany               |
| `Seniority`                         | Seniority level                                  |
| `MainTech`                          | Primary technology used                          |
| `OtherTech`                         | Additional technologies used                     |
| `Yearly brutto salary`              | Annual gross salary in EUR                       |
| `Yearly bonus + stocks in EUR`      | Annual bonus and stock compensation              |
| `VacationDays`                      | Number of vacation days                          |
| `EmploymentStatus`                  | Current employment status                        |
| `Contract duration`                 | Length of employment contract                    |
| `MainLanguage`                      | Primary work language                            |
| `CompanySize`                       | Size of the company                              |
| `CompanyType`                       | Type of company                                  |
| `LostJobDueToCOVID`                 | Job loss status during COVID-19                  |
| `WFHSupportAmount`                  | Work-from-home support amount                    |
| `Month`                             | Month of the survey entry                        |
| `age_group`                         | Categorized age group                            |

## Objective

- Analyze the relationship between demographic factors (**age, gender, city**) and job roles (**Software Engineer, Data Scientist, etc.**).
- Identify **trends in technology usage, work experience, salary, and vacation days**.
- Discover **hidden patterns** using **Multidimensional Category Analysis (MCA)**.
- Understand **workforce dynamics** by assessing employment status, company size, and job security.

## Analysis Outputs

### **Categorical Distribution**

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/1.png)

- The dataset includes **600 male and 200 female employees**.
- **Munich, Berlin, and Frankfurt** have the highest employee concentrations.
- **Software engineering** dominates as the most common role, followed by **Backend Developer** and **Data Scientist**.
- Programming languages like **Python, Java, C++, and PHP** are widely used.
- The majority of employees work **full-time** under indefinite contracts.
- **English, German, and Russian** are the most commonly used languages.

### **Numerical Distribution**

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/2.png)  
![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/3.png)

- The most common **age group** is **30-35 years old**.
- Most employees have **10+ years of experience**.
- Salaries peak around **€60,000**, while bonuses are around **€10,000**.
- Standard vacation policy is **30 days annually**.

### **Multivariate Analysis**

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/4.png)

- **Salaries for Software Engineers** range from **€25,000 to €175,000**.
- **Higher salaries are associated with senior and leadership roles**.
- **Larger companies (1000+ employees) offer more vacation days**.
- **Freelancers in startups have more variable vacation policies**.

### **MCA Analysis**

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/5.png)

- **Senior employees are concentrated in Berlin and Munich**.
- **Female employees** are generally **younger and English speakers**.
- **Large companies employ more full-time workers**, while **startups have more freelancers and part-timers**.
- **Data Scientists and Python**, **Backend Developers and Java/SQL**, **Frontend Developers and JavaScript/TypeScript** are strongly linked.

![image](https://github.com/AtilaKzlts/IT-Survey/blob/main/assets/pics/6.png)

**Proximity Relationship**:  
   - **Close points**: Güçlü ilişkiler (örneğin, büyük şirketlerde tam zamanlı çalışanlar).  
   - **Distant dots**: Zayıf ilişkiler ya da benzersiz özellikler.  
**Clusters and Quartets**:  
   - **Bottom left quadrant**: Küçük firmalar ve startup'lar ilişkisi.  
   - **Bottom right quadrant**: Serbest çalışanlar ve yarı zamanlı çalışanlar ile startup'lar ilişkisi.  
   - **Upper right quadrant**: Benzersiz kategoriler (örneğin, sözleşme süreleri).  
**Company and Labor Relations**:  
   - **Full-time work** büyük şirketlerde yaygın, **freelancers** ve **part-time workers** startup'larda yaygın.


## Detailed Summary

### **Categorical Features**

- **Gender**: The majority are male (700+), with 150 female employees.
- **City**: Berlin and Munich have the highest number of employees.
- **Position**: Software Engineer is the most common job title.
- **Seniority**: More than 300 employees hold senior roles.
- **Main Technologies**: Python and Java are the most widely used.
- **Employment Type**: Most employees work **full-time**.
- **Company Size**: Employees are mainly in mid-sized (51-100) and large (1000+) companies.
- **Company Type**: **Product-based companies dominate** the industry.

### **Numerical Features**

- **Age Distribution**: The majority are **young or middle-aged** professionals.
- **Experience**: Varies widely, with both fresh graduates and experienced professionals present.
- **Salary**: Right-skewed distribution, indicating fewer high earners.
- **Vacation**: Typically **28-30 days annually**.
- **Remote Work Support**: Ranges **475-500 EUR**.

### **Multivariate Analysis**

- **Higher seniority correlates with higher salaries**.
- **Larger companies provide more vacation days**.
- **Full-time work is predominant in large companies**, while **freelancers are more common in startups**.

### **MCA Findings**

- **Backend Developers** → **Java, PHP, SQL**
- **Data Scientists** → **Python**
- **Frontend Developers** → **JavaScript/TypeScript**
- **Senior professionals** are concentrated in **Berlin & Munich**.

### [Return to Portfolio](https://github.com/AtilaKzlts/Atilla-Portfolio)

