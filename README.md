# SQL Fundamentals Project — Data Querying and Sorting

## 📘 Overview
This project was completed in a virtual machine environment and focused on practicing fundamental SQL operations to query and analyze organizational data.  
The tasks involved working with sample tables (`machines` and `log_in_attempts`) to retrieve, filter, and sort information for system and user activity analysis.



## 🧩 Tasks Overview

### Task 1: Display All Columns in the Machines Table
Viewed all available data from the `machines` table to understand the structure of the dataset and the type of information stored.  
This provided a clear overview of all records before applying specific filters or selecting individual columns.



### Task 1.1: Retrieve Email Client and Device ID
Displayed only the `device_id` and `email_client` columns from the `machines` table.  
This allowed for focused analysis of device configurations and identification of specific records such as the third entry.



### Task 1.2: Display Device ID, Operating System, and Patch Date
Selected specific columns — `device_id`, `operating_system`, and `OS_patch_date` — to concentrate on system patch details and OS information.  
This demonstrated how to extract targeted data while minimizing unnecessary output.



### Task 2: View Login Attempts by Country
Extracted login attempt data and corresponding countries from the `log_in_attempts` table.  
This helped visualize where login activity was occurring and provided insight into regional access patterns.



### Task 2.1: Identify Specific Login Attempts
Retrieved usernames with their login dates and times to identify the fifth recorded login attempt and evaluate user activity timing.  
This showcased how SQL queries can be used to pinpoint specific records and analyze event sequences.



### Task 3: Sort Login Attempts by Date and Time
Sorted all login attempt data in ascending order by `login_date` and `login_time` to identify the first recorded login event.  
This process highlighted the usefulness of SQL sorting for identifying earliest or latest activities within a dataset.



## 🧠 Conclusion / What I Learned
During this project, I gained hands-on experience with essential SQL concepts and commands, including:

- Using the `SELECT` statement to retrieve data from tables  
- Applying the `*` wildcard to display all columns in a table  
- Selecting specific columns to extract targeted information  
- Using the `ORDER BY` keyword to sort query results by date and time  
- Identifying specific rows of interest (e.g., first, third, or fifth record)  
- Analyzing login data to track user activity and detect patterns  



## 💻 Environment
This project was performed on a **virtual machine**, interacting with a **sample SQL database** representing an organization’s IT systems and login data.



## 📁 Summary
This project strengthened my understanding of how SQL can be used to query, organize, and analyze structured data.  
It also demonstrated how query-based data extraction supports analysis of system information and user activity — valuable skills for roles in **data analysis**, **information systems**, and **cybersecurity**.
