# Data-Analyst-Devang-Agrawal
Project Description: Descriptive Analysis of Project value and no. of project.

Project Title: Understanding property development trends.

Objective: The primary goal of this project is to conduct a descriptive analysis of issued building permit data from city of Vancouver. Through this analysis, we aim to summarize key characteristics of project type, identify trends, and generate insights that can inform prorty development strategies and inventory management.

Dataset: The dataset includes informational data of issued building permit from city of vancouver over the year <a href="2023_issued-building-permits .xlsx">2023</a> and <a href="2024_issued-building-permits.xlsx">2024</a>, containing the following key features:

•	PermitNumber: Unique identifier for each permit

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

**Data Collection**: downloded the data from city of vancouver (https://opendata.vancouver.ca/explore/dataset/issued-building-permits/information/) for <a href="2023_issued-building-permits .xlsx">2023</a> and <a href="2024_issued-building-permits.xlsx">2024</a> and loaded in stored in S3 Landing zone (<a href="S3 Storage design-2023.png">2023_Landing</a>, <a href="S3 Storage design-2024.png">2024_Landing</a>).

**Data cleaning and structuring**: Used **Amazone Glue dataBrew** ((<a href="S3 Storage design-2023.png">2023_Gluedatabew</a>, <a href="S3 Storage design-2024.png">2024_Gluedatabrew</a>) to clean and restructur the data by removing missing values, deleting unnecessary columns and changing data type.

**Data Privacy and Data Quality**: Used **Amazone Glue** (<a href="S3 Storage design-2023.png">2023_DQDP</a>, <a href="S3 Storage design-2024.png">2024_DQDP</a>) to maintain data privacy and high data quality.

**Descriptive Statistics**:
To	Calculate summary statistics for key variables using <a href="ETL pipeline.png">**AWS GLue ETL pipeline**</a> and <a href="Athena_SQL_result02.png">**AWS Athena**</a>, including:

Total project value by each type of work to calcualte % change in Project value beetwen 2023 and 2024.

total Number of Project for each type of work, to calculate % change in no. of project beetwen 2023 and 2024.

**Data Visualization**: 
Created <a Development trend analysis.pdf">visual</a> representations to illustrate findings using Excell tool:
 
	Bar graph showing change in project value and project count trends over the year.

**Insights and Findings**:

insights derived from the analysis, highlighting:

Project value for the "demolition/deconstruction" and "addition/alteration" significantly increased with minimal change in no. of project, contradicting, "new construction" and "temporary builidng/structure".

**Recomendation**:

Recent dramatically increased housing price and rents mihgt be the combined effect of the decreased no. of new construction and increased interest rate trigering major reform in policy and taxation.

