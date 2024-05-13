# ChatGPT-impact-on-tech-job-market
Impact of ChatGPT on job tech market

The integration of artificial intelligence (AI) technologies has revolutionized various aspects of our lives, and the realm of employment is no exception. Among these innovations, ChatGPT stands out as a versatile tool, capable of understanding and generating human-like text. In this report, we delve into the impact of ChatGPT on the ever-evolving landscape of the technology job market. As organizations increasingly adopt AI-driven solutions, it becomes imperative to examine how ChatGPT influences job roles, skill requirements, and employment dynamics within the tech sector. By analyzing trends, challenges, and opportunities, we aim to provide insights into the transformative effects of ChatGPT on workforce composition, job functions, and career trajectories in the tech industry.

MORE ON DATA:

Let us have a look at the data first. This dataset contains information pertinent to job postings on Indeed, featuring 328,654 entries across 16 distinct columns. The data spans various attributes crucial for job analysis, including details such as the job title, subtitle, location, company name, and URL, among others. Notably, there are missing values in several columns, indicating potential data incompleteness or variability. Key features such as job descriptions, company ratings, review counts, and salary estimates are present, facilitating a comprehensive examination of job market dynamics. Additionally, the dataset provides insights into job posting dates, types, shifts, benefits, and geographic distribution. Given that our analysis primarily focuses on comparing essential data between 2022 and 2023, it's crucial to consider the 'Job Posted Date' column. The varying data types, including objects and float64, suggest a mix of categorical and numerical information, underlining the multidimensional nature of the dataset. Exploring this dataset promises valuable insights into trends, patterns, and opportunities within the job market, enabling informed decision-making and strategic planning for job seekers, recruiters, and policymakers alike.


APPROACH TO THIS DATA ANALYSIS REPORT:

We'll analyze dataset columns for 2022 and 2023 to assess ChatGPT's impact on job market metrics. This comparison will unveil any shifts influenced by AI in job postings, top employers, and job attributes.

ANALYSIS:

1. JOB POSTED DATE:
We'll examine the total job postings for the years 2022 and 2023, excluding any data from 2024 due to its incomplete status.

2. JOB TITLES:
In the dataset, comprising 328,595 entries within the "Job Titles" column, we observe 94,765 distinct job titles. This indicates a diverse range of tech job postings on Indeed during the years 2022 and 2023, underscoring the breadth and variety of employment opportunities within the technology sector during this period.

	The bar plot below shows the most frequently posted job titles in 2022 and 2023.

<img width="562" alt="Frequent Job Titles" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/1184d74f-0a3e-4b66-a188-07d4494792dd">

The most common Job Title in the dataset has been the ‘Software Engineer’ role, without a surprise, with a total 11,327 roles taking around 34% of the total roles.

In 2022, prior to the widespread adoption of ChatGPT in tech companies, a total of 239,560 job postings were recorded, with 65,235 representing unique roles. Contrasting this with 2023, after ChatGPT's integration, the total job postings decreased to 85,140, with 34,938 unique roles. 


Two perspectives emerge from this comparison: 
Firstly, the stark decline in total job postings from 2022 to 2023 suggests multiple factors may have contributed, potentially including the ongoing global recession.
Secondly, examining the proportion of unique roles reveals a notable shift. In 2022, unique roles accounted for 27.23% of total job postings, whereas in 2023, this figure rose to nearly 41.04%. This increase in the percentage of unique roles can be perceived as a positive consequence of ChatGPT's integration within tech companies, indicative of its role in fostering diversity and innovation within job offerings.

3. Total Software Engineer Roles in 2022 and 2023:
Analysis of job postings from 2022 and 2023 reveals a significant emphasis on Software Engineer roles, comprising 34.57% of the total roles posted during this period. Specifically, there were 9,201 Software Engineer roles posted in 2022, whereas only 2,126 were posted in 2023. This trend underscores the persistent demand for Software Engineer talent and potentially reflects fluctuations in industry needs or hiring trends over the analyzed period.

<img width="517" alt="SE Roles" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/513f176d-f8bf-479f-89f2-3f224c27f562">

The pie chart below illustrates a notable disparity in the distribution of job postings across the years 2022 and 2023. Specifically, the majority of job postings are concentrated in 2022, suggesting a significant bias towards this year in terms of hiring activity. This bias may indicate various factors such as economic conditions, industry growth, or specific events influencing hiring trends during the analyzed period.

<img width="557" alt="SE Roles Chart" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/1e2b5668-5996-46c2-893e-12ec67d276d3">

4. JOB DESCRIPTIONS WITH KEYWORDS LIKE AI,ML AND DATA SCIENCE:
Looking at the job descriptions of the jobs posted in 2022 and 2023 which contained keywords like AI, ML or Data Science in them, there were a total of 47218 jobs posted in total (not unique). Out of these 47218, about 33385 of them were posted in 2022 and only ​​13833 were posted in 2023. 

These are the top 20 job roles posted in 2022 that contained these keywords in them:
Top 20 job titles with job descriptions containing keywords like AI, ML, data science posted in 2022:

Software Engineer                                        1197
Data Analyst 					 	 1182
Data Engineer                            		 1056
Senior Software Engineer                  		 793
Machine Learning Engineer                 		 455
Senior Data Engineer                      		 386
Senior Data Analyst (REMOTE)              		 382
Software Developer                        		 300
Senior Data Analyst                       		 297
Business Intelligence Analyst             		 268
Lead Software Engineer                    		 184
Principal Software Engineer               		 184
Full Stack Developer                      		 178
Software Engineer II                      		 171
Network Engineer                             		 168
Senior Machine Learning Engineer          		 150
Sr. Software Engineer                       		 127
Technical Writer                          		 121
Full-Stack Software Engineer (Elixir)     		 115
Database Administrator                    		 108


5. JOB LOCATIONS:
Since 2022, the predominant trend in the United States' tech job market has been the surge in remote positions, surpassing on-site roles. Among on-site positions, New York emerged as the primary hub, closely followed by Chicago, IL.

<img width="608" alt="Job Locations" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/2a1643df-3526-4371-9f5f-0fe9e38150bd">

Additionally, a total of 14,182 tech job opportunities were unveiled in the Bay Area during the combined period of 2022 and 2023, further solidifying its status as a pivotal tech ecosystem.

6. TOP COMPANIES WITH MAXIMUM REMOTE JOB OPENINGS:
In the dataset, the 'Company Rating' column evaluates companies on a scale of 5. This allows us to identify top-performing companies, defined as those with ratings of 4 or above, that offered remote job opportunities during the years 2022 and 2023. The graph below showcases these exemplary companies, providing insights into the leading organizations that prioritize remote work and maintain high ratings for employee satisfaction and performance.

<img width="598" alt="Remote Job Postings" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/0ba065ee-dcc0-46ab-a88b-0217180c9734">

8. TOP JOB OPENINGS IN THE BAY AREA IN 2022 AND 2023:
The graph below illustrates the distribution of job openings across various locations within the Bay Area during the years 2022 and 2023. Given the Bay Area's reputation as a global innovation hub, this analysis sheds light on the geographic focal points of tech industry growth and expansion. By identifying the areas with the highest concentration of job opportunities, we gain valuable insights into the ongoing vibrancy and evolution of the region's tech ecosystem, highlighting its pivotal role in driving technological innovation and fostering global connectivity.

<img width="592" alt="Job Openings in Bay Area" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/5eea9a79-c2cc-4cad-8364-89c992053efe">

9. TOP EMPLOYERS FOR TECH ROLES IN 2023:
The following graph provides a visual representation of the top employers in 2023, offering valuable insights into the leading organizations within the job market during that period. Notably, the absence of a prominent tech product company among the top employers is a surprising observation. Instead, the list primarily comprises companies from diverse sectors, suggesting a shift in employment trends or a broader industry diversification beyond traditional tech product companies. This observation underscores the dynamic nature of the job market and highlights the evolving landscape of employment opportunities across various industries.

<img width="592" alt="Active Employers in 2023" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/cfe4053d-053d-40db-ba92-18028aee4b2f">

10. COMPARISON OF KEY EMPLOYERS AND TOP ROLES: 2022 vs. 2023:
The following graphs offer a comparative analysis between the top employers for tech roles in 2022 and 2023, alongside the predominant job roles opened within these companies during the respective years. This direct comparison aims to illuminate potential shifts or trends within the tech job market over time and explore the influence that ChatGPT may have had on these companies and their roles. By examining changes in both employer composition and role prominence, this analysis provides valuable insights into the evolving landscape of the tech industry and its workforce dynamics. The first graph will be for 2022 and the following graph will be for 2023.

<img width="617" alt="Top 3 hiring companies" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/f11a6bc2-a86f-4050-8591-e78080a62b80">
<img width="611" alt="Top 3 hiring companies 2023" src="https://github.com/Soham-123-Prabhu/ChatGPT-impact-on-tech-job-market/assets/79825092/6fdc1490-1f37-4302-9f4b-88e98dd812e2">

Link to the colab notebook:
https://colab.research.google.com/drive/179M9o7_G58hTSChIHOIb5DL21kxki-pK#scrollTo=Y7vbQkWWtF2Y


