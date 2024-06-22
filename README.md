# Customer Segmentation in the Airlines Industry

This project aims to understand customer segmentation in the airline industry by analyzing flight data. Using clustering techniques, we identify distinct customer segments based on their flight behaviors and demographics. This analysis helps in targeted marketing and improving customer satisfaction.

Understanding customer behavior is crucial for airlines to enhance their services and tailor marketing strategies. This project leverages clustering algorithms to segment customers based on their flight data, providing insights into different customer groups and their characteristics.

## Dataset
The dataset used for this analysis contains information on customer flights, demographics, and loyalty. Key columns include:

MEMBER_NO: Unique identifier for each customer
GENDER: Gender of the customer
AGE: Age of the customer
FFP_DATE: Date of joining the frequent flyer program
FIRST_FLIGHT_DATE: Date of the first flight
SEG_KM_SUM: Total kilometers flown
FLIGHT_COUNT: Number of flights taken
LAST_FLIGHT_DATE: Date of the last flight

## Methodology
Data Cleaning: Handling missing values, converting date columns to appropriate formats, and removing duplicates.
Exploratory Data Analysis (EDA): Understanding the distribution of data and key characteristics of customers.
Feature Engineering: Creating new features such as flight frequency, recency, and customer loyalty tier.
Clustering: Applying clustering algorithms like K-Means to segment customers into distinct groups.
Evaluation: Assessing the quality of clusters using silhouette scores and visualizations.
Results

## The analysis identified several customer segments with distinct flight behaviors and demographics. Key insights include:
Frequent Flyers: Customers who fly often and have high loyalty.
Infrequent Flyers: Customers who fly rarely and might be targeted for engagement campaigns.
New Customers: Recently joined customers who need tailored onboarding experiences.
