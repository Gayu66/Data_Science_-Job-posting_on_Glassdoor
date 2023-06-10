# Data_Science_-Job-posting_on_Glassdoor
The Project is about Data cleaning and transformation. It can be done in Microsoft excel and python too. Here used Excel function to clean data

-----------------------------------------------------------------------------------------------------------------------------------------------------
<h1>Table Content</h1>

- Abstract 
- Problem statement
- Data Description 
- Project outline
- Methodology  
- visualization 
- conclusion 
- References

-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Abstract</h2>

The project "Data Science Job Posting on Glassdoor" aims to analyze and provide insights into the landscape of Data Science job opportunities available
on the Glassdoor platform.
By examining a comprehensive dataset of job postings, this project seeks to uncover trends, patterns, and key information relevant to job seekers 
and employers in the Data Science field.
The methodology involves collecting and analyzing data from job postings on Glassdoor, focusing on various aspects such as job titles, required skills, 
experience level, salary information, and other relevant factors. 

-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Problem statement</h2>

The problem lies in the lack of comprehensive and easily accessible information regarding Data Science job postings on Glassdoor. Job seekers often spend 
significant time and effort manually searching through numerous job listings, making it challenging to identify the most suitable opportunities.
Employers, on the other hand, struggle to understand the evolving demands of the job market, leading to ineffective recruitment strategies and difficulty 
in finding the right candidates.
To address this problem, the project aims to collect and analyze a large dataset of Data Science job postings on Glassdoor. The goal is to uncover trends,
patterns, and key factors influencing Data Science job postings, including job titles, required skills, experience levels, salary ranges.

-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Data Description</h2>

The dataset used for the "Data Science Job Posting on Glassdoor" project consists of a comprehensive collection of job postings related to Data Science 
roles extracted from Glassdoor platform. The data provides insights into the job landscape, requirements, and trends specific to the Data Science field.

The dataset includes the following key features:

  - Job Title: The title or position name of the job posting, representing the specific Data Science role being advertised.

  - Job Description: A detailed description of the job responsibilities, requirements, and expectations for the Data Science position. 

  - Required Skills: The specific skills or technologies mentioned as essential for the Data Science role. This feature helps identify the technical 
    proficiencies expected from job applicants.

  - Experience Level: The desired level of experience for the Data Science position, which can range from entry-level to senior or managerial roles. 
    This information gives an understanding of the experience requirements and career progression opportunities.

  - Salary Information: Information related to the compensation and benefits associated with the Data Science position, including salary ranges or 
    specific salary figures. This feature provides insights into the salary trends and market competitiveness for Data Science roles.

  - Location: The geographical location where the job is based. This feature enables the analysis of regional job markets and highlights areas with a 
    higher demand for Data Science professionals.

  - Company Information: Details about the hiring companies, including their names, industry sectors, and any additional information available. 
    This information allows for an analysis of job opportunities across different companies and industries.


-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Project outline</h2>

   - Explore and analyze job titles ,Numbers are removed from company name
   - Analyze job descriptions and required skills  [ python , excel , hadoo, tableau etc.]
   - Investigate experience level requirements
   - Examine salary information and trends ,Transformed Salary column into integer one
   - Explore geographical distribution of job postings
   - Analyze company profiles and industry sectors

-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Methodology</h2>  
  
  Steps and function used for analysis :
  1. Deleted Index
  2. converted salaray column into normal format and removed doller sign [using FIND & REPLACE]
  3. finding minimum salary [ seperated salary range using ""text to column"" and the used min formula]  
  4. finding max salary [ seperated salary range using ""text to column"" and the used maxformula] 
  5. finding avg salary [ seperated salary range using ""text to column"" and the used avg formula]
  6. find job state using location column [ used ""text to column"" and sepearted location and state]
  7. Finding year [ used formula of  =YEAR(TODAY())-A2 ] (A2 is column of company found year)
  8. find python,excel,hadoop,spark,aws,tableau,big_data used or not used job discription 
     ( formula =IF(ISNUMBER(SEARCH("python",$C2)),1,0) C2 is column of  job discription
 
  9. job_simp it is the -- extracing the name of "" Data Scientist"" from the title of Job 
     Using formula of [ =IFERROR(MID($A2,FIND("Data Scientist",$A2),LEN("Data Scientist")),"na")  ]

  10. Extracing seniority from job title 
      Formula = [ =SUBSTITUTE(IFERROR(MID($A2,FIND("Sr",$A2),LEN("sr")),"na"),"Sr","senior") ]

-----------------------------------------------------------------------------------------------------------------------------------------------------

<h2>Visualization</h2>
  Used small amount of data to do basic visualization and represattion of insights.
   
  ![image](https://github.com/Gayu66/Data_Science_-Job-posting_on_Glassdoor/assets/128694860/7d5de0d4-cb4a-4bc7-8808-deec5941af8d)

  -------------------------------------------------------------------------------------------------------------------------------
  
  ![image](https://github.com/Gayu66/Data_Science_-Job-posting_on_Glassdoor/assets/128694860/00ea6334-d390-491c-bf98-b580020ed954)
  
 -----------------------------------------------------------------------------------------------------------------------------------------------------
 
<h2>conclusion</h2>

In conclusion, the project successfully analyzed Data Science job postings on Glassdoor, providing valuable insights and recommendations for both job 
seekers and employers. The findings shed light on the current job market trends, skill requirements, and salary ranges, enabling individuals to make informed 
decisions and organizations to better understand the competitive landscape in the Data Science domain.

It is important to note that this project has certain limitations. The analysis was based on the available data from Glassdoor, and additional data sources
could provide further insights. Furthermore, the project focused on a specific platform, and the findings may not be representative of the entire job market.
 
 -----------------------------------------------------------------------------------------------------------------------------------------------------
 
<h2>References</h2>
 
   https://www.kaggle.com/
   
   https://www.analyticsvidhya.com
   
   https://machinelearningmastery.com
   
-----------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------

  



