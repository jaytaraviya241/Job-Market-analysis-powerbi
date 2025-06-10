# Analyzing the Data Science Job Market: A Power BI Case Study for DataSearch

In this project, I worked on a real-world-style case study for DataSearch, a fictional recruiting firm specializing in the data science job market. The objective was clear: to create a business-ready dashboard that reveals hiring trends, in-demand skills, and key roles using a rich dataset of job postings. I used Power Query for data wrangling, DAX for analytics, and Power BI for visual storytelling. Here’s a deep dive into the entire pipeline, analysis, and final product.

🔢 The Data Analytics Pipeline
Data Integrity Checks: Ensured minimal missing values and cleaned critical fields.
EDA with Power Query & Power BI: Explored trends in job postings, salaries, job titles, and applicant behavior.
Data Modeling: Utilized a snowflake schema with relationships defined for drill-down analysis.
DAX Calculations: Created measures to calculate average salaries, skill likelihood, job posting trends, etc.
Dashboard Design: Built four interactive dashboards — Homepage, Job Page, Skill Page, and Company Page — focused on user experience and stakeholder queries.
🚀 Problem to Solve
DataSearch needs to understand better the data science job market: which roles are in demand, what skills companies are asking for, and how this varies across industries and time. Recruiters need actionable insights to connect companies with the right talent faster.

🔢 About the Dataset
This fictitious dataset spans 5 years and contains over 8,000 job postings, each with 19 attributes including:

Job Title, Level, Type
Skills Required
Salary Range
Years of Experience
Industry, Company Name, and Size
Date Posted and Applicants in First 24 Hours


Despite being synthetic, the data resembles real market dynamics and helps simulate a genuine analyst experience.

🔍 Initial Exploratory Data Analysis
❌ Missing Values:

90% missing in salary data
31% missing in applicant counts
<1% missing in company and job titles
📅 Job Posting Trends:

March 2020 showed a sharp dip due to COVID-19
Steady increase in postings over the years
⚖️ Experience vs Salary:

Positive correlation observed
Data Analysts earned the least on average
🌐 Market Insights Uncovered
Top Roles:
Data Engineer (most in-demand)
Data Scientist (2nd most posted)
Data Analyst, ML Engineer, and Data Science Manager
Top Skills:
Python, SQL, Power BI, Tableau, AWS, and Excel
Skill cleanup involved standardizing values (e.g., “powerbi” vs “power_bi”)
Industry Trends:
The tech industry dominated job postings
Smaller companies posted most frequently
Competitive salaries are found in the software & internet industries
Job-Level Breakdown:
Entry-Level: Requires Excel, SQL, Tableau
Mid-Level: Adds Python, Cloud
Senior Roles: Demand leadership & data architecture
📊 Key Measures & DAX Insights
Posting Count
Skill Count
Skill Likelihood = Skill Count / Posting Count
Salary Gauges: Average, Min, Max by job level and industry
🔺 Interactive Dashboards
1. Homepage
Overview KPIs and trend summaries with slicers for industry, role, and experience level.


2. Job Page
Drill into specific job titles, required experience, and hiring trends over time.
![image](https://github.com/user-attachments/assets/5ff1cfca-8dfc-497d-a50f-17401f313188)


3. Skill Page
Detailed analysis of top skills, their frequency, likelihood in job postings, and trends by role.
![image](https://github.com/user-attachments/assets/77b291cd-8478-4d6a-8bbf-587a599d23fb)


4. Company Page
View hiring patterns by company name and size, industry-specific demand, and role-skill mapping.
![image](https://github.com/user-attachments/assets/a9169763-637d-495e-bbe2-88d2f1c05cd8)


📊 Recommendations for DataSearch
Focus on sourcing Data Engineers and Data Scientists, especially for Tech & Internet industries.
Train junior talent on SQL, Python, and Power BI to match entry-level demand.
Highlight companies like Topal hiring aggressively in mid to senior roles.
Target small to mid-sized companies for quicker recruiter placements.
🛌 Final Thoughts
This case study was a fantastic opportunity to simulate the role of a business/data analyst in a real-world recruitment context. From dirty data to insightful dashboards, I walked through the entire data analytics pipeline. The final Power BI product equips DataSearch with the ability to make data-driven recruiting decisions, tailored to current market trends.

Recruiters can now simply filter by role, industry, and skills to identify demand gaps and optimize their placements.

[Dashboard report link](https://app.powerbi.com/view?r=eyJrIjoiZTA0MWI0ZjgtOGNkNi00MDBiLWJiNjAtYzY1ZjUzNTNmMTgzIiwidCI6IjYxYTk0OWRjLTBiNDgtNGM3NC1iMDA4LWFjODlkNmU2MTE4YyJ9)
