# Big-Data-

Customer Behavior Analysis Using Python

Project Overview

This project analyzes customer interaction data from an e-commerce environment to understand customer behavior, revenue generation, delivery performance, and customer satisfaction across different channels and product categories.

The analysis was conducted using Python in Google Colab on the dataset customer_events_lab.csv.

Dataset Description

The dataset contains customer events such as product views, purchases, reviews, and returns. Key variables include:

* Event time
* Customer ID
* Country
* Sales channel
* Device
* Product category
* Customer action
* Delivery time
* Rating
* Revenue

Tools Used

* Python
* Pandas
* Matplotlib
* Google Colab

Data Quality Checks

The dataset was reviewed for missing values in:

* Country
* Device
* Rating
* Delivery Time

Not all missing values were considered data-quality issues. For example:

* Missing ratings are expected when the action is not a review.
* Missing delivery times are expected when the action is not a purchase.

Business Questions Answered

1. Which channel generates the highest total revenue?
2. Which product category generates the highest total revenue?
3. Which country has the highest number of customer events?
4. Which channel has the slowest average delivery time?
5. Which category has the highest average rating?

Key Findings

1. Mobile App Generates the Highest Revenue

* Total Revenue: 61,258.22

Business Action:
Invest further in the mobile application through customer engagement initiatives and app-exclusive promotions.

2. Electronics Generates the Highest Revenue

* Total Revenue: 65,616

Business Action:
Prioritize inventory management and marketing efforts for electronics products.

3. Germany Records the Highest Customer Activity

* Customer Events: 2,087
* UK Customer Events: 808
* Ireland Customer Events: 428

Business Action:
Focus marketing and retention strategies on the German market while investigating opportunities to increase engagement in other countries.

4. Partner Marketplace Has the Slowest Delivery Time

* Average Delivery Time: 60.52 minutes

Business Action:
Review logistics processes and third-party fulfillment performance to improve customer experience.

5. Customer Ratings Are Relatively Consistent Across Categories

* Highest Average Rating: Grocery (3.58)
* Lowest Average Rating: Books (3.25)

Business Action:
Monitor customer feedback but prioritize operational improvements, as rating differences are relatively small.

Visualizations

The project includes visualizations showing:

* Customer activity by country
* Revenue by sales channel

Big Data Concepts

Volume

The dataset contains customer event records that would continue growing as more customers interact with the business.

Velocity

Customer events can be generated continuously in real time through purchases, reviews, and website activity.

Variety

The dataset includes numerical, categorical, boolean, and datetime data.

Veracity

Some missing values exist, but several are expected based on business processes.

Value

The analysis provides actionable insights for revenue growth, customer engagement, and operational improvement.

Data Governance

To protect customer privacy, customer IDs should be anonymized before analysis. This prevents customer identification while still allowing meaningful business insights to be generated.

Data Pipeline

Customer Activity → CSV Database → Customer ID Anonymization → Data Cleaning → Data Analysis → Dashboard → Business Decision

