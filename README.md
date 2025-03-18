# EDA-of-Flipkart-Customer-Support-Performance
* Data Understanding & Preprocessing:

I collected and explored Flipkart's customer support data.
Cleaned the dataset by handling missing values, removing duplicates, and ensuring data consistency.
Converted date-time columns for time-based analysis to better understand trends and patterns over time.

* Complaint Trends (Line and Bar Charts):

I filtered out missing data and grouped complaints by month and support channel (e.g., email, chat).
Line Chart: I used this to track how the number of complaints changed over time (month by month).
Bar Chart: I used this to compare the number of complaints in different product categories (such as electronics or clothing).

* Response and Handling Time Distribution:

I calculated response time and handling time after converting the Issue_reported at and issue_responded columns to datetime format.
Histogram with KDE: I used this to visualize the distribution of response times and handling times, helping to understand whether most complaints are resolved quickly or if some take longer.

* Top 10 Customer Cities:

I counted how many issues came from each customer city and focused on the top 10 cities with the most complaints.
Bar Chart: I used this to show the number of complaints from each of these top 10 cities, identifying regions with the highest issue count.

* CSAT Score Distribution:

I visualized the distribution of customer satisfaction (CSAT) scores to understand customer feedback.
KDE Plot: I used this to understand how satisfied customers were by visualizing the spread of CSAT scores.

* Pair Plot Analysis:

I used a pair plot to visualize the relationships between multiple variables (e.g., response time, handling time, and CSAT scores).
This helped me identify patterns, correlations, or outliers between the features, offering deeper insights.

* Correlation Heatmap:

I used a heatmap to visualize correlations between numerical features such as response time, handling time, and CSAT score.
This helped me understand which features were positively or negatively correlated, providing valuable insights into how they might impact each other.
These steps helped me uncover trends and patterns in customer complaints, response times, customer satisfaction, and locations. The pair plot and heatmap allowed me to explore deeper relationships between the data features, enhancing the overall analysis.

I used Python for data processing and visualization, and Jupyter for executing the analysis and displaying the results.

#python #jupyter #flipkart #EDA #dataanalysis #data #visualization

https://github.com/Tanveerr97/EDA-of-Flipkart-Customer-Support-Performance/blob/main/Yes_Bank_Stock_Performance_Analysis%20copy.ipynb

