# purdue-corec-tracker
Using Purdue's CoRec/recreational facilities can sometimes be inconvenient due to large crowds. Although Purdue provides a website displaying current facility occupancy, it lacks an intuitive way to explore historical data. This program visualizes occupancy levels over time and analyzes usage patterns to identify trends and quieter hours.

MVP:
Extract current occupancy data from Purdue's RecWell website.
Store occupancy readings, capacities, and timestamps in an SQLite database.
Collect occupancy data periodically to build a historical dataset.
Display occupancy trends using graphs.

Future Plans
Compare occupancy trends across different days of the week.
Identify the quietest and busiest hours at the CoRec.
Add search and filtering options for different recreational facilities.

Tech Stack: 
Language: Java
HTTP Requests: Java HttpClient
JSON Parsing: Gson
Database: SQLite with JDBC
Visualization: JavaFX

Website Data Source: https://www.purdue.edu/recwell/facility-usage/

Project Documentation:
Eisenhower Matrix
System Diagram

Currently in the planning stage.
