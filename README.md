# Data-Analyst-Devang-Agrawal
Project Description: Descriptive Analysis of Project value and no. of project.

Project Title: Understanding property development trends.

Objective: The primary goal of this project is to conduct a descriptive analysis of issued building permit data in city of Vancouver. Through this analysis, we aim to summarize key characteristics of project type, identify trends, and generate insights that can inform prorty development strategies and inventory management.

Dataset: The dataset includes informational data of issued building permit from city of vancouver over the year 2023 and 2024, containing the following key features:

•	PermitNumber: Unique identifier for each permit

<a href="2023_issued-building-permits .xlsx">RESULT</a>

•	PermitNumberCreatedDate: explaining when the permit no. created.

•	IssueDate: explaining when the permit was issued

•	PermitElapsedDays: time requires to issue permit form the date of creation.

•	Project Value: explaining the total project cost 

•	TypeOfWork: permit issue for which type of project (e.g. demolition, salvage, new builing)

•	Address: Location of the project.

•	Project discription: Describe the details of the project.

•	Applicant name: Name of the applicant applied for the permit.

•	Applicant address: location of applicant.

•	Project discription: Describe the details of the project.

**Data Collection**: downloded the data from city of vancouver (https://vancouver.ca/home-property-development.aspx) for 2023 and 2024 and loaded in stored in S3 Landing zone.

**Data cleaning and structuring**: using Amazone Glue dataBrew to clean and restructur the data by removing missing values, deleting unnecessary columns and changing data type.

**Descriptive Statistics**:
To	Calculate summary statistics for key variables using AWS GLue ETL pipeline and AWS Athena, including:

Total project value by each type of work to calcualte % change in Project value beetwen 2023 and 2024.

total Number of Project for each type of work, to calculate % change in no. of project beetwen 2023 and 2024.

Data Visualization: 
	Create visual representations to illustrate findings using Excell tool:
	Bar graph showing change in project value trends over the year.
	Bar charts displaying the most popular product categories.
	Pie charts representing the share of different payment methods.
	Heatmaps of sales by location and time of day.
