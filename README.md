**Flight Data Analysis and Reporting — SQL Project**

📌 **Introduction**
This project is a comprehensive SQL-based analysis of an airline database that simulates real-world flight operations. The goal is to derive actionable insights for key stakeholders—including airline management, operations teams, and customer service—by querying operational data such as flight schedules, bookings, revenues, seat occupancy, and more.

All SQL queries were written and tested on MySQL Workbench, adhering to best practices such as aliasing, performance optimization, and result formatting.

🧠 **Key Business Objectives**
Monitor flight delays and punctuality

Measure aircraft utilization and seating efficiency

Analyze revenue generation by route and booking patterns

Understand passenger behavior from bookings to boarding

✅ **Tasks Performed**
This project includes solutions to 17 real-world business questions grouped under multiple airline analytics themes:

✈️ **Flight & Aircraft Operations**
Calculate delay in departures for late flights

Measure aircraft utilization by number of flights

Analyze average flight duration by aircraft model

Assess occupancy rate per aircraft

💺 **Passenger & Boarding Analysis**
Average boarding number and total passengers per flight

Frequent routes and route-level boarding patterns

Distribution of ticket sales by fare condition

Total spend per passenger across all journeys

💰 **Revenue & Booking Insights**
Total and top 3 revenue-generating flights

Daily booking trends (volume and revenue)

Hourly peak booking activity

Revenue by route (departure → arrival pair)

🗂️ **Dataset and Schema Overview**
The project operates on a normalized relational schema containing the following key entities:

Table	Description
aircrafts	Aircraft specifications like model and range
airports	Geographical and metadata on airports
flights	All flight records including scheduled & actual times
bookings	Passenger bookings and payment data
tickets	Individual tickets tied to bookings
ticket_flights	Ticket and flight link with fare details
boarding_passes	Passenger boarding data with order number
seats	Aircraft-wise seat configurations

**🛠️ How to Use This Project**
Environment:
Install and configure MySQL Workbench or any compatible SQL interface.

Database Setup:
Use the airlines_schema_scripts.sql to populate your database. The schema includes all required tables with relevant sample data.

Run the SQL Script:
Open the provided .sql file (Template_for_learners.sql) in MySQL Workbench and execute it section-by-section to analyze results for each business problem.

Query Customization:
You may tweak conditions (e.g., filter by aircraft model, specific date ranges, or airports) to tailor the analysis for other scenarios.

📈 **Sample Output Highlights**
Flight ID 1021 had a delay of 37 minutes

Aircraft A320 operated the most flights (85), averaging 135.6 mins per flight

Top revenue-generating route: DEL → BOM, earning ₹6.5M+

Fare condition ‘Business’ led in average ticket revenue

📁 **File Structure**
pgsql
Copy
Edit
- Template_for_learners.sql       # Main SQL script with all query solutions
- Flight Data Analysis and Reporting_Problem_Statement.pdf
- README.md                       # This file

🙌 **Acknowledgements**
This project is part of an applied learning assignment to demonstrate SQL data analytics on aviation data. Thanks to vLearn Platform for the structured schema and real-world problem statement.
