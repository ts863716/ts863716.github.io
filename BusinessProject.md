[Home](https://ts863716.github.io/)

### Business Project using SQL and Power BI 

## Business Request & User Stories

The business request for this project was an executive sales report for sales managers. Based on the request that were made from the business, the following user stories were defined to fulfill delivery and ensure that acceptance criterias were maintained throughout the project.

| As a (role) | I want (request / demand) | So that I (user value) | Acceptance Criteria |
| --- | --- | --- | --- |
| Sales Manager | To get a dashboard overview of internet sales | Can follow better which customers and products sells the best | A Power BI dashboard which updates data once a day |
| Sales Representative | A detailed overview of Internet Sales per Customers | Can follow up my customers that buys the most and who we can sell more tos | A Power BI dashboard which allows me to filter data for each customer |
| Sales Representative | A detailed overview of Internet Sales per Products | Can follow up my Products that sells the most | A Power BI dashboard which allows me to filter data for each Product |
| Sales Manager | A dashboard overview of internet sales | Follow sales over time against budget | A Power Bi dashboard with graphs and KPIs comparing against budget |

## Data Cleansing & Transformation (SQL)

To create the necessary data model for doing our analysis and fulfilling the requirements above, the following tables were extracted using SQL

```SQL
SELECT * FROM table
```
