# Customer Shopping Behavior Analysis

End-to-end analysis of 3,900 customer purchase records using Python and SQL, built to answer real business questions about revenue, shipping preferences, discounts, and customer loyalty.

## What this project does

- Cleans and prepares raw shopping data in Python/Pandas
- Loads the cleaned data into a MySQL database
- Answers 10 business questions using SQL (revenue by gender, discount behavior, top products, shipping comparison, customer segmentation, and more)
- Summarizes findings in a presentation for a non-technical audience

## Key findings

- Female customers generate slightly more total revenue than male customers
- Express shipping customers spend ~12% more per order than Standard shipping customers
- About half the customer base are first-time buyers — repeat-purchase conversion is the biggest growth lever
- Subscribed customers spend more per transaction and purchase more frequently than non-subscribers

## Dashboard

Built an interactive Power BI dashboard on top of the same dataset — filterable by subscription status, gender, category, and shipping type. Shows revenue and sales breakdowns by category and age group, average purchase amount, and average review rating.



## Tools used

- Python (Pandas, SQLAlchemy)
- MySQL
- SQL
- Power BI
- Gamma AI (presentation design)

## Project structure

```
├── customer_shopping_behavior.csv   # raw dataset
├── New_p.ipynb                       # data cleaning + MySQL load (Python)
├── Project.sql                       # 10 business-question SQL queries
├── dashboard.pbix                    # Power BI dashboard
├── dashboard.png                     # dashboard screenshot (for preview, since GitHub can't render .pbix)
├── requirements.txt                  # Python dependencies
├── .env.example                      # template for DB credentials (copy to .env, do not commit .env)
└── .gitignore
```


## Notes

This project was built end-to-end by me — data cleaning and SQL analysis are original work. The presentation slides were generated using Gamma AI based on the analysis findings.
