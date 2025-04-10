## sql_challenge
## Employee Data Analysis Project
## Project Overview
Welcome to the SQL Challenge! This project involves working with historical employee data from Pewlett Hackard (a fictional company) to analyze the workforce from the 1980s and 1990s. Your task as a data engineer is to import the provided CSV files into a relational database, design the appropriate schema, and answer key business questions through data analysis.

# Project Goals
This project is divided into three main phases:

## Data Modeling

Create an Entity Relationship Diagram (ERD) to visualize relationships between data tables.
Data Engineering

Define the schema for six CSV files, specifying data types, primary keys, and foreign keys.
Import data from the CSV files into SQL tables while maintaining relational integrity.
Data Analysis

Use SQL queries to extract insights about employees, departments, and their roles.
Repository Setup
Create a Repository:

Create a new GitHub repository named sql-challenge.
Clone the Repository:

Clone the repository locally using the following command:
bash
Copy code
git clone <repository_url>
Organize Files:

Inside the repository, create a directory named EmployeeSQL to store all project files.
Add the downloaded project files to this directory.
Push Changes:

Commit and push your local changes to GitHub.
Project Files
CSV Files:
Six CSV files containing employee and department data.

## SQL Script Files:
Scripts for table creation, data insertion, and analysis queries.

## Entity Relationship Diagram:
A visual representation of the table relationships (e.g., created using QuickDBD).

Instructions
# 1. Data Modeling
Review the provided CSV files to understand the structure and relationships between data.
Sketch an ERD to model the relationships. Tools like QuickDBD or dbdiagram.io are recommended.
# 2. Data Engineering
Write SQL scripts to:
Create tables for all six CSV files.
Define appropriate data types, primary keys, and foreign keys.
Use NOT NULL constraints where necessary.
Ensure tables are created in the correct order to handle dependencies.
Import CSV data into the tables using INSERT or a database-specific import tool.
# 3. Data Analysis
Write SQL queries to answer the following:

List the employee number, last name, first name, sex, and salary of each employee.
List the first name, last name, and hire date for employees hired in 1986.
List the manager of each department with their department number, department name, employee number, last name, and first name.
List the department number for each employee along with their employee number, last name, first name, and department name.
List the first name, last name, and sex of employees whose first name is "Hercules" and last name starts with "B".
List all employees in the Sales department, including their employee number, last name, and first name.
List all employees in the Sales and Development departments with their employee number, last name, first name, and department name.
List frequency counts of all employee last names in descending order.
Deliverables
SQL Scripts:

schema.sql: Script to create tables with the correct schema.
import.sql: Script to load data from CSV files into the database.
queries.sql: Script with the required analysis queries.
ERD File:

A diagram representing the data model (e.g., PNG or PDF).
Analysis Results:

Include query outputs or screenshots of results in the repository.
