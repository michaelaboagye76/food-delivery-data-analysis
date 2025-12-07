## Delivery Performance Analysis: Python and Tableau Insights for Operational Efficiency


## Overview

This project analyzes delivery performance using Python and Tableau to uncover insights that improve delivery efficiency, customer satisfaction, and restaurant operations.
The dataset contains fields related to delivery duration, rider wait time, preparation time, customer information, traveled distance, and restaurant attributes.



## Data Cleaning and Preparation (Python)

Key steps:

* Removed missing values using `dropna()`.
* Converted time strings (e.g., `"11:30"`, `"12:45"`) into timestamps with `pd.to_datetime()`.
![](/images/datetime.png)
* Parsed complex datetime formats such as `"11:38 PM, September 10 2024"`.
* Selected and organized columns by datatype.
* Engineered additional metrics:

  * Total delivery duration
  * Rider wait time
  * Preparation duration
  * Distance categories
  * Delivery efficiency indicators



## Python Visualizations

Developed foundational visualizations for exploratory analysis, including:

* Delivery time distribution

* Distance vs. delivery duration

* Boxplots of preparation time by restaurant

* Rider wait time vs. delivery duration

  

* Correlation heatmap using seaborn

  ![](/images/Screenshot from 2025-12-06 21-57-28.png)

* Pairwise relationships among numerical variables

  ![](/home/michael/Desktop/FOOD DATA ANALYSIS/images/numeric relation.png)




## Key Insights

* Preparation time contributes more to delays than travel distance.
* Delivery times peak during evening hours.
* Rider wait time is highest at high-volume restaurants with slower workflows.
* Short-distance deliveries still face delays due to kitchen bottlenecks.
* Customers show strong loyalty to consistently fast restaurants.



## Technologies Used

* Python (pandas, numpy, seaborn, matplotlib)
* Tableau 
* Excel for data export and formatting



## **Additional Information**

Refer to the slides to view tableau visualizations.