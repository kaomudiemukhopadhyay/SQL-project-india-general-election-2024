India General Election Result Analysis 2024 (SQL Project)
📌 Project Overview
This SQL project analyzes the India General Election 2024 dataset using SQL Server.

The project focuses on:
Party performance
Alliance performance (NDA / I.N.D.I.A / OTHER)
State-wise seat distribution
Winning margins
Candidate performance
EVM vs Postal votes
Maharashtra state summary
Top candidates by votes

This project demonstrates real-world SQL skills such as joins, aggregations, window functions, ranking, CTEs, grouping, filtering, and schema understanding.

🎯 Business Problem
Election data is large and spread across multiple tables.
The objective was to transform raw relational data into meaningful insights using SQL.

🛠 Tools Used
Tool	Purpose
SQL Server	Querying & analysis
SSMS	SQL execution
GitHub	Project hosting
Excel / CSV	Dataset storage
Draw.io / PowerPoint	ERD design
🗂 Dataset Tables
Table Name	Description
partywise_results	Party names and seats won
constituencywise_results	Winning candidate by constituency
constituencywise_details	All candidates and vote counts
statewise_results	Constituency-state mapping
states	State master table

🧩 ERD / Schema
<img width="803" height="465" alt="image" src="https://github.com/user-attachments/assets/04b39f03-0f79-4dd6-8be3-bb1694ca4a57" />

🔥 SQL Skills Used
SELECT
WHERE
GROUP BY
ORDER BY
JOIN
COUNT()
SUM()
MAX()
CASE WHEN
ROW_NUMBER()
CTE (WITH)
PARTITION BY
DISTINCT
ALTER TABLE
UPDATE

📊 Key Analysis Questions Solved
1. Total seats available in each state
2. Total seats won by NDA alliance
3. Total seats won by I.N.D.I.A alliance
4. State-wise alliance seat breakdown
5. Highest EVM vote candidate in each constituency (Top 10)
6. Winner and runner-up in each constituency of Maharashtra
7. Maharashtra summary:
Total seats
Total candidates
Total parties
Total votes
EVM votes
Postal votes

📈 Key Insights
NDA won highest total seats.
State-wise results vary significantly.
EVM votes dominate over postal votes.
Some constituencies had close victory margins.
Maharashtra had multi-party competition.

🚀 How to Run
Import CSV files into SQL Server
Run schema.sql
Run analysis_queries.sql
