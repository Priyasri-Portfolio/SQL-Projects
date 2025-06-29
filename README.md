* SQL Projects 1:

This Project showcases a basic relational database design for a university course enrollment system. It includes 
Entity Relationship Diagram(ERD), SQL schema creation, data insertion, example queries, and a brief report.

* SQL Project 2:

* Project Overview
This Project showcases advanced SQL analysis skills through a financial investigation scenario. The challenge involves analyzing WSDA Music. Using real-world business data, the goal is to uncover inconsistencies in financial records from 2011-2012 and identify the individual responsible for the missing funds.

* Objective:
  - Perform detailed analysis of transaction data to spot unusual patterns
  - Generate a list of potential suspects using SQL-driven investigation
  - Apply advanced SQL techniques such as JOIN, subqueries, and aggregation
  - Demonstrate data forensics through structured querying
 
* Database Structure
  The analysis is based on three key tables:
  - Customers: Contains customer details and purchase history
  - Employees: Includes sales staff and commission-related info
  - Invoices: Stores transaction data such as purchase dates and totals
 
* Analysis Workflow

  Challenge 1: Overall Financial Snapshot
    - Count total transactions for 2011-2012
    - Calculate revenue generated during this period

  Challenge 2: Customer & Staff Behavior
    - Identify all customers who made purchases in the investigation timeframe
    - Link each customer to their sales rep using the Join operations
    - Highlight transactions exceeding the average value
    - Compare average transaction amounts by year

  Challenge 3: Suspect Discovery
    - List employees with above-average sales performance
    - Calculate 15% commission for each salesperson using arithmetic and sum
    - Find the top-earning rep
    - Identify data anomalies and irregular records
    - Determine the main suspect based on findings

* SQL Techniques used:
    - MULTI-TABLE JOINS for relational exploration
    - Subqueries for comparative logic
    - Aggregate function: COUNT, SUM, AVG
    - WHERE and HAVING for conditional filtering
    - Mathematical operations for commission calculations
    - ORDER BY and GROUP BY for structured outputs
    - Logical conditions and nested filtering
    - 
