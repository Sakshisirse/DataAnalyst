# Data Analyst
## Customer Support Data Analysis
This project explores and analyzes customer support ticket data to gain insights into issue patterns, resolution efficiency, and communication channel effectiveness.
## Introduction
Efficient customer support is vital for maintaining user satisfaction and loyalty. This analysis leverages a dataset of 40,000 support tickets to explore trends in issue categories, communication channels, resolution outcomes, and response times.
## Dataset Description
The dataset contains 40,000 records with the following columns:
ticket_id	Unique identifier for the support ticket
, customer_id	Unique customer ID
, customer_name	Name of the customer
, email	Customer email address
, issue_category	Type of issue (e.g., Shipping, Billing)
, channel	Contact medium (e.g., Email, Chat)
, resolution	Ticket outcome (e.g., Resolved, Escalated)
, response_time_hrs	Time taken to respond (in hours)
, timestamp	Date the ticket was created
## Data Cleaning & Preprocessing
Steps performed:
Converted timestamp to datetime format.
Verified missing values (none found).
Checked for outliers in response_time_hrs.
Removed or masked PII for privacy if needed.
Standardized categorical values.
## Exploratory Data Analysis (EDA)
Key analyses:
Frequency of tickets by issue_category.
Average response_time_hrs per channel.
Resolution status distribution.
Time series of ticket volume over months.
## Visual Insights
Typical visualizations (to be generated):
Bar Chart of issues per category.
Box Plot of response times by resolution type.
Pie Chart for communication channel distribution.
Line Graph for ticket trends over time.
## Conclusion
The dataset reveals:
Most frequent issues are related to Shipping and Billing.
Phone and Email are dominant contact channels.
Escalated issues tend to have longer response times.
Resolution efficiency varies by channel and issue type.
These insights can help optimize resource allocation and improve customer satisfaction.
## Requirements
To run the analysis:
Pandas
Python
dask
NLP techinques
## authors
this project was developed by Sakshi Sirse
