# EDA-of-Flipkart-Customer-Support-Performance
*  Data Understanding & Preprocessing
Collected and explored Flipkart's customer support data.
Cleaned the dataset by handling missing values, removing duplicates, and ensuring data consistency.
Converted date-time columns for time-based analysis.

* Complaint Trends (Line and Bar Charts):

I filtered out the missing data and grouped the complaints by month and the support channel used (like email or chat).
Line Chart: I used this to track how the number of complaints changed over time (month by month).
Bar Chart: I used this to compare the number of complaints in different product categories (like electronics or clothing).

* Response and Handling Time Distribution:

I calculated the response time and handling time after converting the Issue_reported at and issue_responded columns to datetime format.
Histogram with KDE: I used this to visualize the distribution of response times and handling times, helping to see whether most complaints are resolved quickly or if some take longer.

* Top 10 Customer Cities:

I counted how many issues came from each customer city and focused on the top 10 cities with the most complaints.
Bar Chart: I used this to show how many complaints each of these top 10 cities had, so I could identify regions with the highest issue count.

* CSAT Score Distribution:

I visualized the distribution of customer satisfaction (CSAT) scores.
KDE Plot: I used this to understand how satisfied the customers were, by visualizing the spread of the CSAT scores.
These steps helped me uncover trends and patterns in customer complaints, response times, customer satisfaction, and locations.
