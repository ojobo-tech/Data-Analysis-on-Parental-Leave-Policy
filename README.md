# Parental-Leave-Policy
The goal of this project is to analyse data for parental leave in the business world using SQL and PowerBI, then create an impactful visual for an article on parental leave policies across the business world, highlighting key insights.

Analysis: Parental Leave in the Business World (SQL and PowerBI)

The past two years have drained people's social, mental, financial, and physical well-being, and parents have had to juggle even more than usual.
But this difficult time has also caused many to reevaluate the importance of work-life balance, shifting the needle on the value of family leave.

Parental leave is a major consideration for job seekers and employers wanting to hire them. On the one hand, employees want to know that their companies will support their family planning goals and accommodate a healthy work-life balance. On the other hand, parental leave - whether paid or unpaid - often presents significant business challenges.
This project represents an impactful visual for an article on parental leave policies across the business world.

In this project, we reviewed 1601 companies across various industries in the USA, focusing on obtaining data about the duration of maternal and paternal leave (paid or unpaid) within their company.

Key Terms and Meanings:
- Maternity leave, i.e. leave for mothers in the weeks immediately preceding and following birth
- Paternity leave, i.e. leave for fathers or, in many cases, recognized second parents to the child, which is usually also given in the immediate period after birth - in some countries even before birth
- Paid Maternity Leave: Paid weeks off from work for mothers after the birth of their child
- Unpaid Maternity Leave: Unpaid weeks off from work for mothers after the birth of their child
- Paid Paternity Leave: Paid weeks off from work for fathers after the birth of their child
- Unpaid Paternity Leave: Unpaid weeks off from work for fathers after the birth of their child

Project Goal
The goal of this project is to create an impactful visual for an article on parental leave policies across the business world, highlighting key insights.
Project Strategy

I downloaded the dataset from Maven Analytics and it contained information about companies, industries, parental leave durations. I performed all data preparation and analysis using SQL (MySQL), and all the SQL codes will be provided below. The visualizations and dashboard were designed with MS PowerBI respectively.

Project Steps:
Data Cleaning and Processing
1. Exploratory Data Analysis
2. Leave Duration Status based on companies.
3. Leave Duration Status based on Industries
4. Key Data Insights
5. Data Visualisation
6. Recommendations based on Data Insights

Data Cleaning and Processing
This dataset is bound to have null, misspelled values. The data was cleaned and processed by checking for missing values, checking for duplicates, and finally cleaning by altering some column names.

Analysis
1. Exploratory Analysis

1a. Total Number of Companies and Industries Surveyed
The analysis showed that there are 1601 surveyed belonging to 186 industries in total.

1b. How many companies paid maternity compared to paid paternity leave?
A total of 1548 companies gave their staff paid maternity leave while only 257 companies gave their staff paid paternity leave. This shows that ~97% of the companies gave women paid maternity leave compared to only 16% giving men paid paternity leave.

1c. How many companies gave unpaid maternity compared to unpaid paternity leave?
Only 647 companies gave their staff unpaid maternity leave while 1551 companies gave their staff unpaid paternity leave. This shows that ~97% of the companies gave men unpaid paternity leave compared to 40% giving women unpaid paternity leave.

1d. What's the average duration of parental leave by gender?
I found the companies that gave women maternity leave gave a maximum of 52 weeks and an average of 17 weeks leave. While the companies that gave men paternity leave gave an average of 1.6 weeks of leave.

1e. What's the average duration of parental leave by gender based on payment status?
I found the companies that gave paid parental leave gave women an average of 11 weeks while men received 1.3 weeks. While the companies that offered unpaid parental leave gave women an average of 6 weeks unpaid while men received 0.3 weeks unpaid leave.

2. Leave Duration Status based on companies.
These are the key insights based on the leave status offered by companies.

2a. What is the number of companies that gave paid maternity leave but no paid paternity leave?
Of the 1548 companies that gave their staff paid maternity leave, 1291 gave their paid maternity leave, but no paid paternity leave, with an average leave period of 11 weeks.

2b. Which companies gave the highest paid maternity leave duration?
We found out that the top 5 companies that give their staff the highest duration of paid maternity leave are ASML, Netflix, Intact Financial Corporation, Veritas Law, and Scentsy; with a leave duration of 52 weeks each.

2c. Which company has the highest paid paternity leave duration?
We found out that the company that gives their staff the highest duration of paid maternity leave is Grant Thornton (51 weeks)

3. Leave Duration Status based on industry.

3a. What are the Top 5 Industries with the most companies that offer paid maternity leave but no paid paternity leave?
We found out that the 5 industry sectors with the most companies that gave their staff paid maternity leave but no paid paternity leave are Technology: Software (136), Advertising (48), Educational Services: College & Universities (47), Technology: Consumer Internet (46), Information Services: Technology (42). While all the companies that offered paid paternity leave also offered paid maternity leave to their female staff.

3b. What are the Top 5 Industries with the most paid paternity leave duration?
We found out that the 5 industry sectors with the most paid paternity leave duration in weeks are Healthcare: Telemedicine (30), Philanthropy (26), Information Services: Financial (23), Information Services: Diversified (18), Finance: Venture Capital (18).

3c. What Industry has the highest paid maternity leave duration?
We found out that the industry sector with the most paid paternity leave duration in weeks is Transportation: Bus (52). The transportation (Bus) sector may have given the highest duration of paid maternity leave because of the rigor of driving a bus.

3d. What Industry has the highest unpaid paternity leave duration?
We found out that the industry sector with the highest unpaid paternity leave duration in weeks is Hospitality: Restaurants (29).

3e. What Industry has the highest unpaid maternity leave duration?
We found out that the industry sector with the highest unpaid maternity leave duration in weeks is Technology: Software (11).

4. Key Insights from the Analysis
The analysis showed that there are 1601 surveyed belonging to 186 industries in total.
- ~97% of the companies gave women paid maternity leave compared to only 16% giving men paternity leave.
- Women received an average of 17 weeks of maternity leave. Men received an average of 1.6 weeks of paternity leave.
- 1291 companies across 179 industries give women paid maternity leave and no paid paternity leave for men. 
- Technology: Software is the industry with the most companies in this category.
- The transportation (Bus) sector gives the highest duration of paid maternity leave (52 weeks).

6. Recommendations based on Data Insights
SHRM and Oxford Economics published findings in 2020 that revealed 'the competitive advantages employers gained by offering paid parental leave: Employee health and wellness: 61%, Employee engagement: 60%, Ability to attract talent: 58%, Employee retention: 55%'.
Some benefits of Improved Leave Conditions to Companies:
- Improved employee retention: Knowing that their companies offer paternity leave can also be an incentive for employees who plan to start families in the future to remain with their employers.
- Increased productivity: With sleep deprivation caused by nighttime feedings and the stress of a new set of responsibilities at home, new fathers may not be fully present on the job even when they're physically there.
- Better workplace morale: Paternity leave programs can be a selling point for your business with quality candidates for open positions, particularly if you're in a state that doesn't require family leave.
