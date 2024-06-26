# oews-capstone

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Motivation](#motivation)
- [Technologies](#technologies)
- [Data](#data)
- [Challenges](#challenges)
- [Conclusions](#conclusions)
- [Dashboard](#dashboard)
- [Sources](#sources)

# Motivation
[(Back to top)](#table-of-contents)
# Analyzing wage and industry trends to help both job seekers and employers.
# I have chosen this project because I am currently working on the Occupational Employment and Wage Statistics (OES) survey for the state of Tennessee’s Labor and Workforce Department. I am working on collecting the data and compiling the data for submission to the federal government’s Bureau of Labor Statistics (BLS). We do some analysis with the data we collect, but that is not our primary focus—the analysis is left more to the BLS. I think it will be interesting to see the analyses I can create with the dataset as someone who is well-acquainted with the data in a different capacity, and I am excited to have the opportunity to create visualizations with data very similar to the data I am working on at my job every day. 
# In addition, as a person currently seeking employment, I am interested in learning more about industry and wage trends. While I may not be able to find information as specific as, say, how much a data analyst makes in Nashville, Tennessee, at specific employers, I do still think the information will be valuable. Even just knowing industry wages across the country can be helpful in determining a fair wage as someone seeking employment. Finally, I had my classmates and even some family and friends in mind while creating this dashboard. Many of my Nashville Software School classmates are seeking employment as well, and I would like to give everyone the same knowledge about wages and industries that I am using for myself.


# Technologies
[(Back to top)](#table-of-contents)
# <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />                   
# <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />            # <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black"/>                  
# <img src="https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white" /> 

# Data
[(Back to top)](#table-of-contents)
# OEWS data was initially found on data.gov.
# The most recent OEWS data was downloaded directly from the Bureau of Labor Statistics Website.
https://www.bls.gov/oes/current/oes_tn.htm 

# Challenges
[(Back to top)](#table-of-contents)
# The primary challenges when it came to analyzing the data and dashboarding were due to missing data and the formatting of the data.
# Some data initially appeared missing, but was actually mislabeled as “hourly” or “annual”. This was fixed in Microsoft Excel. Some entries were missing wage data. These entries were removed in Microsoft Excel, and some found later were dropped in Microsoft Power BI.

# As someone who collects this data, I know from the other side of things that there are some issues with industry standardization. 
# Basically, the industry each job entry is grouped as is up to each employee. As employees, we are presented the raw data and then format it to fit the Bureau of Labor Statistics formatting. This includes categorizing each job title under a “SOC code”. While there are guidelines on how to categorize each job, there is still some room for interpretation. I may categorize a job under a certain SOC code, but my coworker may categorize the job under a different SOC code. The Bureau of Labor Statistics uses its own website for coding and storing the data, and this system may accept both mine and my coworker’s categorizations as correct. Usually this will only happen to a certain degree, a computer systems job will not be successfully coded as a warehouse job, but a computer systems job may be accidentally coded as a computer security job without issue. In addition, the employees coding the jobs have to go off of what the employer told them the job title was. If an employer is saying the job title is a management position it will be coded that way, but sometimes “office manager” would be more correctly titled as “office clerk”, the employer has just always called the job an office manager and is not too concerned with the technical differences between the positions. Both of these issues could cause the data to be misrepresentative of certain industries and job titles. There is a possibility that certain job titles may not have accurate counts of employees or average wages due to this problem with standardization.

# Conclusions
[(Back to top)](#table-of-contents)
# In conclusion, analyzing wage and industry statistics is important for many different groups all for varying reasons.
# For entities such as the Tennessee Department of Labor, using OEWS statistics is helpful in analyzing how the state of Tennessee compares to other states in the country when it comes to average annual and hourly wages. For employers, these statistics can be beneficial in determining fair wages for their employers. Lastly, and perhaps most importantly, analyzing OEWS statistics can be beneficial to job seekers so they can be prepared with industry and wage knowledge and ensure they are being compensated fairly for their field and location.

# Dashboard
[(Back to top)](#table-of-contents)
# Link to dashboard.
# https://app.powerbi.com/groups/me/reports/29e3f9bc-0538-4a9d-80f9-c8c12601e70d/ReportSectionb757a3d39f2f8881b516?experience=power-bi

# Sources
[(Back to top)](#table-of-contents)
# https://data.gov/
# https://www.bls.gov/oes/current/oes_tn.htm
# https://www.bls.gov/oes/oes_emp.htm


