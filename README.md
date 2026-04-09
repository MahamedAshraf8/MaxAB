# MaxAB
MaxAB Data Analysis Challenge: Collection Efficiency and Cost Optimization
Project by: Mohamed Ashraf Basha
Junior Data Analyst | 01016251696 | mohamedashraf04q@gmail.com

Project Overview
This project focuses on analyzing operational data for MaxAB, a leading B2B e-commerce platform. The goal was to evaluate collection order performance, agent productivity, and provide strategic recommendations to optimize costs between digital and manual payment methods.

Tech Stack
SQL Server (T-SQL): For data extraction, self-joins, and complex aggregations.

HTML/CSS: For creating a professional, interactive results dashboard.

Data Analysis: Trend analysis, productivity benchmarking, and cost-benefit analysis.

Key Analysis Phases
1. Collection Performance (Question 1)
Weekly Success Rate: Calculated the ratio of successful collections (Collected/Partially Collected) to monitor operational stability.

Agent Efficiency: Used Self-Joins to measure the average duration from "Task Started" to "Task Finished" for each agent.

Zone Productivity: Benchmarked zones based on the Orders-to-Agent ratio.

High Pressure: Zone 11 (321.5 Orders/Agent).

Underutilized: Zone 28 (125.0 Orders/Agent).

2. Cost Optimization (Question 2)
Analyzed the financial impact of two recharge methods:

Digital (UPG Wallet): Variable cost of 0.61%.

Manual (Collection): Fixed cost of 17.5 EGP per transaction.

Identified cost-saving opportunities by shifting POS users toward digital adoption.

Strategic Recommendations (Part D)
Based on the data-driven insights, I proposed:

Dynamic Resource Re-allocation: Moving agents from low-productivity zones to high-pressure zones to balance workload.

Route Optimization: Implementing GPS-based route planning to minimize transit times in slower zones.

Digital Incentive Programs: Incentivizing POS retailers to use digital wallets, significantly reducing the fixed costs associated with manual collections.

Repository Structure
/SQL_Queries: Contains all .sql scripts for performance and cost analysis.

/Dashboard: The interactive HTML file for project presentation.

/Documentation: PDF reports and methodology.

How to View the Dashboard
Download the index.html file from the /Dashboard folder.

Open it in any modern web browser.
