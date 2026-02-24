# Bike Buyers Demographic & Sales Analysis Dashboard
### Business Problem
A bicycle retail company wants to understand the behavior and demographics of their customers to identify the key factors influencing purchasing decisions. The management needs a clear, interactive dashboard to analyze how variables such as income, commute distance, age, and education correlate with bike purchases. The goal is to profile the "ideal customer" to optimize marketing strategies and sales targeting.

###  Tools & Technologies Used
•	Microsoft Excel: The primary tool used for the entire data lifecycle.

•	Data Cleaning & Transformation: Utilized Remove Duplicates, Find & Replace for standardizing categorical data (e.g., converting "M" to "Married"), and Nested IF statements for creating new data categories (Age Brackets).

•	Pivot Tables: Used to summarize raw data and create aggregations for analysis.

•	Pivot Charts: Created bar charts and line graphs to visualize trends.

•	Slicers: Implemented interactive filters for Marital Status, Region, and Education to allow users to drill down into specific customer segments.

### 📊 Key Analysis Performed
1.	Removed duplicate records to ensure data integrity.
   
2.  Standardized abbreviations (e.g., "M" to "Male", F to “Female”, M to “Married”,     "S" to "Single") to make the dashboard user-friendly.
  
4.	Created a custom "Age Bracket" column using nested-if formulas to group individual ages into broader categories ("Adolescent", "Middle Age", "Old") for clearer trend analysis.
Example: =IFS(L2<31,"Adolescent",L2<55,"Adult",L2>54,"Elderly")

4.	Visualization & Dashboarding:
__Average Income per Purchase: Compared the average income of buyers vs. non-buyers, segmented by gender.
Commute Distance Analysis: Analyzed the relationship between the distance a customer lives from work and their likelihood of purchasing a bike.
Age Group Trends: Visualized sales volume across different age brackets.

<img width="850" height="553" alt="Bike Sales DB" src="https://github.com/user-attachments/assets/0348c974-95f3-4585-b4a7-b0aaa7dbe87a" />



### 💡 Key Insights
•	Income Factor: Customers who purchased bikes generally have a higher average income compared to non-buyers. Additionally, male customers in this dataset tended to have slightly higher incomes than female customers.

•	Commute Distance: There is a negative correlation between commute distance and bike purchases. Customers with short commutes (0-1 miles) are the most likely to buy a bike, while those with long commutes (10+ miles) are less likely.

•	Age Demographics: Middle-Aged customers (defined as roughly 31-54 years old) are the largest consumer segment for bikes. Adolescents (<30) and older demographics (55+) show significantly lower purchase rates.

•	Marital Status: Married individuals constitute a significant portion of the customer base and tend to have higher average incomes than single individuals.

### Recommendations
•	Target Marketing: Focus marketing campaigns heavily on the Middle-Aged (31-54) demographic, as they are the primary purchasers.
•	Location-Based Strategy: Prioritize advertising in residential areas located within a 0-5 mile radius of major business hubs or workplaces, as short commuters are high-potential leads.
•	Pricing Strategy: Since bike buyers tend to have higher incomes, there may be an opportunity to introduce premium models or accessories to this specific segment.

