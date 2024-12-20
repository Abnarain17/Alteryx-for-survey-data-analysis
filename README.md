# Alteryx-for-survey-data-analysis
Using Alteryx for Survey Data Analysis: A Hands-On Project Guide 
Overview: This project provides learners with a hands-on experience using Alteryx to 
analyze sales and profit data. Learners will utilize Alteryx to work with survey data from a 
company that sells multiple products to various customers. By the end of the project, 
participants will gain a deeper understanding of customer survey results, consumer 
preferences, and other critical business insights. 
Skill Prerequisite: To participate in this project, learners should have: 
1. Basic knowledge of data analytics and data visualization. 
2. Familiarity with Alteryx, Microsoft Excel, and basic professional software. 
System Prerequisite: For the project, learners will need the following system setup: 
1. A Windows operating system (Windows 7 or later) with at least 4 GB of RAM. 
2. The latest version of Alteryx installed on the system. 
3. Microsoft Excel installed. 
4. Access to the provided data files. 
5. An internet connection for accessing online resources and documentation. 
Dataset: The dataset for this project consists of survey data from two sources: the "Data" 
input containing responses and the "Questions" input containing associated questions. 
The goal is to create an output file that is user-friendly and formatted appropriately for 
further analysis. The data requires cleaning, parsing, and merging to achieve the desired 
output format. 
Objective: The goal of this project is to analyze survey data from the two sources using 
Alteryx and create an output file that details responses by age for each individual. The file 
should be organized in a way that facilitates easy visualization using tools such as Tableau, 
Qlik, or PowerBI. 
Detailed Objective: The project aims to analyze customer feedback data from multiple 
sources to generate insights that can help improve company services. The data is stored 
across three sources: "Survey Responses," "Customer Information," and "Service Logs." The 
following tasks need to be completed using Alteryx: 
1. Import data from all three sources using the input tool. 
2. Combine survey responses and customer data using the join tool, matching 
customer IDs. 
3. Extract date and time information from service logs using the formula tool. 
4. Join the service logs with the combined survey and customer data based on date 
and time. 
5. Remove incomplete or irrelevant records using the filter tool. 
6. Separate the comment field in the survey data into individual fields for analysis 
using the text-to-columns tool. 
7. Summarize the data by service type and calculate the average rating and sentiment 
for each group. 
8. Calculate the time difference between service request dates and survey response 
dates. 
9. Filter out records where the survey response was completed too long after the 
service request. 
10. Summarize the data by service representative and calculate the average rating and 
sentiment for each representative. 
11. Calculate the percentage of positive, neutral, and negative comments for each 
service representative. 
12. Export the results to a CSV file for further analysis and visualization. 
By performing these tasks, the company can obtain actionable insights into areas of 
improvement in customer service. The final output will provide details on the average 
ratings and comment sentiment for each service type and representative, as well as the 
distribution of positive, neutral, and negative feedback. This information will be valuable in 
developing targeted training programs, improving customer service, and enhancing the 
overall customer experience. 
Note: 
1. The column "Column" in the "Questions" file corresponds to the field header value 
in the "Data" file. For instance, a value of 38 in the "Questions" file corresponds to 
the question associated with field F38 in the "Data" file. 
2. The first row in the "Data" file contains the response type. In field F38, the data is 
formatted as "Response (Scale 1-10) - Age Range." 
Tasks: To successfully complete this project, follow these steps using Alteryx: 
1. Import the survey data from the "Data" input using the input tool. 
2. Skip the first row of the survey data using the sample tool. 
3. Transpose the columns of the survey data into rows. 
4. Trim the "F" prefix from the column names using the formula tool. 
5. Import the question data from the "Questions" input using the input tool. 
6. Use the select tool to choose the required fields from the question data. 
7. Join the question labels to the survey data table using the join tool by connecting the 
outputs of the select tool and the trim function. 
8. Filter the data to include only questions 28 and 38 using the filter tool. 
9. Cross-tabulate the data to place questions in their own rows. 
10. Parse the search experience question for the first number in the string using the 
regex tool. 
11. Parse the age range from the data using the regex tool. 
12. Remove unnecessary fields, rename columns, and adjust variable sizes using the 
select tool. 
13. Execute the workflow by clicking "Run" and use the browse tool to view the output. 
14. Save the workflow for future use. 
Conclusion: In conclusion, this project demonstrates the power of Alteryx in data 
transformation and cleaning. By analyzing survey data across several years and from 
multiple products and customers, the project uncovers insights that can drive business 
improvements. The project highlights the importance of using tools for data cleaning, 
transformation, and analysis, allowing businesses to make informed decisions. 
This experience will enable learners to understand the critical role of data cleaning in the 
data analysis process, which ultimately helps businesses reduce waste and optimize 
resources. 
Project Summary: This project offers learners practical experience with using Alteryx for 
data transformation and cleansing. By the end of the project, learners will have developed 
skills in handling and analyzing large datasets, which they can apply in future data-related 
projects. Additionally, the project emphasizes the importance of data cleaning for making 
informed business decisions and ensuring the quality of analysis.
