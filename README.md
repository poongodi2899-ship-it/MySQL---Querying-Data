# 📊 Employee Management SQL Querying & Analytics Project

# 📌 Project Overview

This project demonstrates the implementation of SQL querying techniques using an Employee Management Database in MySQL. It covers data retrieval, filtering, sorting, grouping, aggregation, joins, and window functions to generate meaningful business insights from relational data.

The project is designed to strengthen SQL fundamentals and analytical querying skills commonly used in Data Analytics, Business Intelligence, and Database Management roles.


# 🎯 Project Objectives

- Retrieve and analyze employee data using SQL queries
- Apply filtering and conditional logic using SQL operators
- Perform data aggregation and summary reporting
- Implement grouping and post-aggregation filtering
- Establish relationships using various JOIN operations
- Generate analytical reports using Window Functions
- Develop practical SQL problem-solving skills
- Extract business insights from structured data

# 📊 Project Highlights

## ✅ Clause & Operators
- DISTINCT
- Alias (AS)
- WHERE Clause
- Comparison Operators
- Logical Operators

## ✅ Sorting & Limiting Data
- ORDER BY
- LIMIT

## ✅ Aggregate Functions
- SUM()
- AVG()
- MIN()
- MAX()
- COUNT()

## ✅ Grouping & Filtering
- GROUP BY
- HAVING
  
## ✅ Join Operations
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- CROSS JOIN
- SELF JOIN

## ✅ Window Functions
- RANK()
- DENSE_RANK()
- Running Total

# 🏗️ Database Structure

The project utilizes three relational tables connected through primary and foreign key relationships.

## Employees
Stores employee information including:

- Employee ID
- Employee Name
- Gender
- Age
- Hire Date
- Designation
- Salary
- Department ID
- Location ID

## Departments
Stores department master information:

- Department ID
- Department Name

## Locations
Stores location master information:

- Location ID
- Location Name

# 🔗 Database Relationships
## Departments → Employees
One department can contain multiple employees.

## Locations → Employees
One location can contain multiple employees.

## Employees → Departments & Locations
Employees are linked to Departments and Locations using Foreign Key relationships.

# 📋 SQL Tasks Implemented
## 1️⃣ DISTINCT VALUES
Retrieve unique salary values from the Employees table.

## 2️⃣ ALIAS (AS)
Provide meaningful aliases for employee age and salary columns.

## 3️⃣ WHERE CLAUSE & OPERATORS
- Filter employees with salary greater than ₹50,000
- Retrieve employees hired before a specific date
- Update missing designation values

# 📈 Sorting & Grouping Operations
## ORDER BY
Sort employees by:

- Department ID (Ascending)
- Salary (Descending)

## LIMIT
Retrieve the first five employees hired during 2018.

## Aggregate Functions
Perform:

- Total salary calculation
- Average salary analysis
- Minimum age identification
- Maximum salary reporting
## GROUP BY
Generate reports for:

- Maximum salary by location
- Average salary by analyst designation
## HAVING
Filter grouped results based on:

- Department employee count
- Average employee age by location

# 🤝 Join Operations

## INNER JOIN
Retrieve employee details along with department information.

## LEFT JOIN
Display all departments including departments without employees.

## RIGHT JOIN
Display all locations including locations without assigned employees.

## CROSS JOIN
Generate all possible combinations between departments and locations.

## SELF JOIN
Identify employee pairs working within the same department.   


# 📊 Window Functions
## RANK()
Rank employees according to salary across the organization.

## DENSE_RANK()
Assign department-wise salary rankings.

## Running Total
Calculate cumulative salary expenditure within each department.


# 📈 Business Insights Generated

- Department-wise salary distribution
- Location-wise employee allocation
- Employee ranking based on compensation
- Workforce demographic analysis
- Department staffing reports
- Salary trend evaluation
- Organizational performance insights

 # 🛠️ Technologies Used
- MySQL
- SQL
- Relational Database Management System (RDBMS)

# 📚 Skills Demonstrated

- SQL Query Writing
- Data Filtering
- Data Manipulation
- Data Aggregation
- Relational Database Management
- Multi-Table Joins
- Window Functions
- Business Reporting
- Data Analysis
- Problem Solving

# 🚀 Business Benefits

- Improves employee data analysis
- Supports management reporting
- Enhances business decision-making
- Enables workforce performance tracking
- Simplifies organizational reporting
- Provides actionable data insights
  
# 📌 Conclusion
This project showcases practical SQL querying techniques through real-world employee management scenarios. By implementing filtering, sorting, aggregation, joins, grouping, and window functions, the project demonstrates how SQL can be used to transform raw organizational data into valuable business insights.
