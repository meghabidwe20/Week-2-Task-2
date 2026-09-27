Task 2 – Exploratory Data Analysis 
India Job Market 2024–2026 
1. Project Overview 
This project performs Exploratory Data Analysis (EDA) on an India Job Market dataset covering job 
postings from 2024–2026. 
The purpose of this project is to understand patterns and relationships in the job market using 
statistical analysis and data visualization. 
The analysis focuses on: 
• Job posting trends 
• Salary distribution 
• Applicant distribution 
• Industry-wise job demand 
• City-wise job demand 
• Work-mode analysis 
• Experience-level analysis 
• Relationship between salary, applicants, and openings 
• Monthly job-posting trends 
2. Objective 
The main objective of this project is to perform comprehensive EDA and uncover: 
• Patterns in job postings 
• Salary distributions 
• Applicant behavior 
• Industry trends 
• Location-based hiring patterns 
• Work-mode differences 
• Experience-level trends 
• Correlations between numerical variables 
• Time-based hiring trends 
The project also provides data-driven insights and business recommendations based on the analysis. 
3. Dataset Description 
Dataset Name: India Job Market 2024–2026 
The dataset contains job-market information such as: 
Column 
Job ID 
Company 
Job Title 
Industry 
City 
Work Mode 
Description 
Unique identifier for a job posting 
Company that posted the job 
Position/job role 
Industry category 
Job location 
Remote, Hybrid, or On-site 
Experience Level Required experience level 
Salary LPA 
Openings 
Applicants 
Salary offered in Lakhs Per Annum 
Number of available positions 
Number of applicants 
Company Rating Company rating 
Date Posted 
Date on which the job was posted 
The dataset used in this project was supplied as: 
india_job_market_2024_2026(1).csv 
4. Technologies Used 
Programming Language 
• Python 3.x 
Libraries 
• Pandas 
• NumPy 
• Matplotlib 
• Seaborn 
• SciPy 
Development Environment 
• Jupyter Notebook 
• Google Colab 
5. Project Structure 
Task_2_India_Job_Market_EDA/ 
│ 
├── data/ 
│  
│ 
 └── india_job_market_2024_2026.csv 
├── notebooks/ 
│  
│ 
 └── Task_2_India_Job_Market_EDA.ipynb 
├── visualizations/ 
│   
│   
│   
│   
│   
│   
│   
│  
│ 
├── 01_salary_distribution_kde.png 
├── 02_applicants_distribution_kde.png 
├── 03_correlation_heatmap.png 
├── 04_salary_by_work_mode.png 
├── 05_top_industries.png 
├── 06_monthly_job_trend.png 
├── 07_salary_vs_applicants.png 
 └── 08_openings_vs_applicants.png 
├── reports/ 
│   
│   
│   
│   
│   
│   
├── descriptive_statistics.csv 
├── correlation_matrix.csv 
├── industry_analysis.csv 
├── work_mode_analysis.csv 
├── experience_level_analysis.csv 
├── city_analysis.csv 
│   
├── monthly_trend.csv 
│   
│  
│ 
├── insights.txt 
 └── Task_2_EDA_Report.pdf 
└── README.md 
6. Visualizations 
6.1 Salary Distribution with KDE 
A histogram and KDE curve were used to understand the distribution of salaries. 
Purpose: 
• Understand salary concentration 
• Identify spread 
• Observe possible skewness 
• Identify extreme salary values 
6.2 Applicants Distribution with KDE 
A histogram with KDE was created for the number of applicants. 
Purpose: 
• Understand applicant distribution 
• Identify highly competitive postings 
• Observe the spread of applicant counts 
6.3 Correlation Heatmap 
A correlation matrix was created for numerical variables. 
The heatmap helps identify relationships between: 
• Salary 
• Openings 
• Applicants 
• Company Rating 
Important: Correlation indicates association and does not prove causation. 
6.4 Salary by Work Mode 
A box plot was created to compare salary distributions across: 
• Remote 
• Hybrid 
• On-site 
This helps identify differences in salary levels and variation across work modes. 
7. Key Insights 
The analysis generated several data-driven insights, including: 
1. The industry with the highest number of job postings was identified from the dataset. 
2. The city with the highest number of job postings was identified. 
3. Work modes were compared based on their average salary. 
4. The correlation between salary and applicants was calculated. 
5. The correlation between openings and applicants was calculated. 
6. Monthly job-posting activity was analyzed to identify peak and low periods. 
All numerical results are calculated directly from the supplied dataset. 
8. Business Recommendations 
Based on the EDA, the following recommendations can be considered: 
Recruitment Planning 
Organizations can use industry and city-level job demand to plan recruitment and sourcing activities. 
Salary Benchmarking 
Salary differences across work modes can be considered when performing compensation analysis. 
Applicant Competition 
Applicant volume relative to available openings can help identify highly competitive job postings. 
Workforce Planning 
Monthly job-posting trends can help recruitment teams plan staffing and hiring capacity. 
Experience-Based Recruitment 
Experience-level analysis can help organizations understand which candidate groups are most 
represented in job demand. 
9.  Deliverables 
The project includes: 
• Complete Jupyter Notebook 
• Descriptive statistics 
• Correlation matrix 
• Grouped analysis 
• 8 visualizations 
• Data-driven insights 
• Business recommendations 
• PDF-ready EDA report 
• Project README 
10. How to Run the Project 
Step 1 – Install Python 
Install Python 3.x on your system. 
Step 2 – Install Required Libraries 
Open Command Prompt or Terminal and run: 
pip install pandas numpy matplotlib seaborn scipy openpyxl 
Step 3 – Open Jupyter Notebook 
Run: 
jupyter notebook 
Step 4 – Open the Notebook 
Open: 
notebooks/Task_2_India_Job_Market_EDA.ipynb 
Step 5 – Run the Notebook 
Run all cells from top to bottom. 
The notebook will generate: 
• Statistical summaries 
• Charts 
• Correlation analysis 
• Grouped analysis 
• Insights 
11. Conclusion 
This project demonstrates how Exploratory Data Analysis can be used to understand an India job
market dataset. 
The analysis combines statistical methods and visualizations to investigate: 
• Salary patterns 
• Applicant behavior 
• Hiring demand 
• Industry trends 
• City-level patterns 
• Work-mode differences 
• Experience-level requirements 
• Monthly job-posting trends 
The results provide a foundation for further analysis such as dashboard development, recruitment 
analytics, salary prediction, applicant prediction, and machine-learning models. 
12. Author 
Name: Megha Bidwe 
Project : Task 2 – Exploratory Data Analysis 
Dataset : India Job Market 2024–2026 
Tools : Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy 
