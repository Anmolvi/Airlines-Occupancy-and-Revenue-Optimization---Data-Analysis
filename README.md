✈️ Airline Data Analytics Case Study – SQLite + Python


📘 Project Overview

This project analyzes an airline’s operational data to identify ways to increase aircraft occupancy rates and optimize revenue per seat.
Using SQLite3 for data management and Python (Pandas, Matplotlib, Seaborn) for exploratory data analysis (EDA) and visualization, the project demonstrates how SQL and Python can work together to solve real business problems in aviation.

The data set is available on keggle: https://www.kaggle.com/datasets/datalearn/airlines-db

🧩 Business Problem

The airline faces several challenges impacting profitability:

Stricter environmental regulations increasing operational costs

Higher flight taxes reducing demand

Rising fuel and labor costs

Pressure to improve occupancy and pricing strategies

The objective is to analyze flight, booking, and ticket data to uncover insights that help:

Improve seat occupancy rates

Develop data-driven pricing strategies

Identify revenue opportunities across aircraft types


⚙️ Tools & Technologies

Category  -	 Tools Used  -  Purpose

Database  -	 SQLite3  -	 Store and query airline data

Language  -	 Python  -	 Data processing & analysis

Environment  -	 Jupyter Notebook  -	 Interactive analysis

Libraries  -	 Pandas, Matplotlib, Seaborn, SQLite3  -	 Data manipulation & visualization


📂 Dataset Summary

Data was stored in a SQLite database containing multiple tables such as:

Aircrafts – aircraft type and capacity

Flights – flight schedules and routes

Tickets & Bookings – ticket sales and booking amounts

Boarding Passes – seat assignments and passenger data

The data was queried directly from SQLite into Pandas DataFrames for analysis.


🔍 Exploratory Data Analysis (EDA)

Steps Performed:

Loaded database tables using sqlite3 and inspected schema.

Queried and merged data for analysis in Pandas.

Analyzed ticket sales, revenue, and occupancy trends.

Created visualizations with Seaborn and Matplotlib.

Key Insights:

Ticket bookings increased steadily from late June to early July.

Revenue trends closely followed ticket sales volume.

Business class fares are consistently higher across all aircrafts.

The SU9 aircraft generated the highest total revenue due to competitive pricing.

The CN1 aircraft underperformed with only economy class tickets and low demand.

A 10% increase in occupancy showed significant potential revenue growth.


📊 Visualizations

Line chart – Tickets booked and revenue over time

Bar chart – Average fare comparison by aircraft and fare condition

Occupancy rate chart – Booked seats vs total capacity

Scenario chart – Revenue growth if occupancy increases by 10%

Each visualization supports strategic recommendations for pricing and seat utilization.


💡 Business Insights

Airlines should focus on dynamic pricing strategies based on aircraft type and fare condition.

Balanced pricing (neither too high nor too low) can improve occupancy and overall profitability.

Increasing occupancy by even a small percentage has a direct positive effect on total revenue.

Maintaining service quality and safety while optimizing prices is essential for sustainable growth.

🧠 Conclusion

This project showcases how SQLite3 and Python can be combined for efficient airline data analysis — from querying large datasets to generating actionable business insights.
Through EDA and visualization, the analysis reveals how adjusting pricing and occupancy strategies can enhance profitability and competitiveness in the airline industry.

The data set is available on keggle: https://www.kaggle.com/datasets/datalearn/airlines-db
