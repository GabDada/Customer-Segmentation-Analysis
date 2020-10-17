### CUSTOMER SEGMENTATION ANALYSIS: ECOMMERCE CASE STUDY

##### BACKGROUND
As businesses increasingly grow their share of online revenue via ecommerce channels, the resulting volume and velocity of data pose new challenges to understanding customer behavior. This sort of scale requires structured analytical approaches to keep track of customer behavior for critical business use cases.

Customer segmentation involves exploring existing relationships between customers while grouping them based on common attributes. Visual and statistical inspection of these segment data can offer really valuable business insights, helping make informed decisions in targeted marketing, new product development, sales forecast, customer support, to mention a few.

In this project, we will carry out customer segmentation analysis for an eCommerce business using transaction data that spans a year. We will be using techniques such as RFM (Recency, Frequency, and Monetary Value), K-Means clustering while also attempting to forecast sales for a year-ahead period using prophet library. Upon successful execution, we want to be able to answer some of the following business questions:

##### Business questions

* Which customer segment accounted for the highest sales in the year under review, and for each operating market?

* What is the size, and average spend per basket for customers in this segment?

* In terms of products, what are the leading sales drivers for each customer segment?

These are some insights certain business stakeholders might be looking to glean from data in their day-to-day operations.

##### Dataset
One year transactional data for an online retail store. The dataset contains 500K records with 8 attributes namely:  Customer ID, Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, and Country.

```
df = pd.read_excel("https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx")
```

[Source here](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx)


##### Objectives
The following tasks will be achieved in the course of this project:
* Perform exploratory data analysis and cleaning in preparation for modeling
* Forecast sales using prophet library
* Segmentation Analysis with RFM
* Segmentation Analysis with K-Means Clustering
* Build a Dashboard for Insights on sales and customer segments
* Attempt to answer our business questions

##### Technologies Used
* Python
* Pandas
* Scikit-Learn
* Numpy
* Seaborn
* Prophet
* Matplotlib
* Plotly
* Bash


```
#let's go!

```
