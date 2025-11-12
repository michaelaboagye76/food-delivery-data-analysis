
### **Project Title:**

**Food Delivery Efficiency Analysis**

### **Objective:**

To analyze food delivery performance data and identify key factors influencing delivery efficiency and customer satisfaction.

### **Data Description:**

The dataset contains delivery-related attributes such as delivery person details, vehicle condition, customer ratings, restaurant and delivery coordinates, and delivery time.

**Key Columns:**

* `Delivery_person_Age`: Age of the delivery person.
* `Delivery_person_Ratings`: Average rating received by the delivery person.
* `Restaurant_latitude`, `Restaurant_longitude`: Restaurant location.
* `Delivery_location_latitude`, `Delivery_location_longitude`: Customer location.
* `Vehicle_condition`: Condition rating of the delivery vehicle (0–3).
* `multiple_deliveries`: Number of deliveries made in a single trip.
* `Time taken (mins)`: Total time taken to complete the delivery.

### **Analysis Approach:**

1. Data cleaning and preprocessing.
2. Compute delivery distance using geospatial coordinates.
3. Perform exploratory data analysis (EDA) to identify relationships affecting efficiency.
4. Correlation and regression analysis to determine key predictors of delivery time.
5. Summarize insights and propose strategies for improvement.

### **Tools and Libraries:**

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (optional for modeling).

### **Expected Outcomes:**

* Insights on how age, ratings, distance, and vehicle condition affect delivery time.
* Identification of patterns to optimize route planning and delivery scheduling.
* Data-driven recommendations for operational improvements.

