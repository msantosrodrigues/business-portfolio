## CONTENTS:
- Jupyter notebook with data treatment
- .xlxs file with resuling data (the original data is very large, a 1GB .csv file)
- [Looker Studio dashboard](https://lookerstudio.google.com/reporting/6d78513b-cb26-4c17-bb32-a9f98b407947) using the resulting data

## Data Analyst II

### Goal
This assessment is designed to evaluate your ability to work with large datasets,
write efficient queries, data modeling and dashboard creation from raw data.
Please complete the tasks below using the dataset provided.

You are provided with a file called purchases.csv containing over 1.8 million records.
Your goal is to extract meaningful information from it.

The purchase_gmv column is normalized between -1 and 1. To denormalize it, you can apply any
reasonable mean and standard deviation of your choice, simulating a real Gross
Merchandising Value (GMV) distribution. Please document the assumptions you
used.

### Part 1 - Data exploration
Imagine this table is stored inside a database of our choice (MySQL, Redshift,
PostgreSQL, etc). Write SQL-like queries that would return:
1. Retrieve the number of products who made purchases in at least 3
consecutive months.
2. Calculate the denormalized GMV share of each country and source
combination.
Send your queries together with your final documentation.

### Part 2 - Dashboard design
Executives in the company want a dashboard that helps them monitor the health of
the business based on user purchasing behavior. They will use this dashboard weekly
in leadership meetings.

Design a dashboard using the dataset provided and the BI tool of your choice.
Send the dashboard file (or a PPT with screenshots and your storytelling)
together with your final documentation.

### Extra - Data modeling (optional)
The company is growing and wants to better understand user purchasing behavior.
You are asked to help structure a new data model that supports both performance
(for queries) and flexibility (for analytics and reporting).

You're given a raw dataset with purchase-level granularity (similar to the one you’re
working with in this test). How would you design the data model for an analytics
database or data warehouse?

Include in your answer:
- Suggested tables and relationships
- Grain of each table
- Any fields or derived tables you would create to optimize analytical queries
(e.g., for user behavior, product performance, retention).

### Submission
You should send the files/materials/documents you used to complete the challenge
via the Greenhouse link provided.
Your test will be reviewed and we will get back to you with feedback and information about
the next steps, if applicable.

***Thank you!***
