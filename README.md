# Cafe-Harmony-Analysis
Analysis on Café Harmony, to detemine the general buisness performance in terms of Sales, Products and Customer Experience.
![Cafe Harmony](https://github.com/user-attachments/assets/74447316-6ae8-442b-993f-aaffd527a8cb)


## Introduction
Café Harmony is a vibrant and emerging virtual café chain known for its diverse selection of beverages, snacks, and light meals. Over the past year, the brand has experienced rapid growth and is now navigating the challenges of scaling operations to meet rising customer demand. 
With several branches spread across the city, each location comes with its own performance indicators and distinct customer tastes.

## Business Problem 
Café Harmony is experiencing rapid growth and now aims to enhance both operational efficiency and customer satisfaction. To achieve this, the company must identify its top-performing menu items across locations, understand the customer segments that generate the highest revenue, optimize stock levels to prevent shortages and overstocking, and evaluate performance at both the location and employee levels.

## Methodology
MS Excel was the preferred tool for the client, so I acquired the datasets for the cafe, which were in 5 different sheets namely: 
- Sales Data
- Customer Data
- Employee Data
- Feedback Data
- Stock Data

I applied data wrangling and cleaning techniques on the datasets, which involved removing duplicates and blanks on all sheets, creating a new column for Age group on the Sales Data, re-structuring the data by merging Sales Data with Customer Data because they both had a unique column which was the Customer ID. Then I created Pivot Tables for proper analysis and finally built a dashboard for visualisation and uncovering insights.

  ## Dashboard
![Cafe Harmony Dash](https://github.com/user-attachments/assets/5d357b56-50c9-46f2-b6f4-3e450ea86b6b)


## Key Findings
Menu Performance:

![Product Revenue 1](https://github.com/user-attachments/assets/36e0d7d9-34d5-472e-bf47-f8e5adccc29e)

From the Product Revenue chart for all locations above, the top-selling menu item that generated the most revenue is the Muffin at $2,401. It also doubles as the most preferred item.
Using the Sales Location slicer on the Dashboard, I was able to deduce that Muffin performed best at Airport ($626) and Uptown ($729), while Iced Tea generated the most revenue at the Suburb ($659) and Downtown ($645). Cappuccino followed closely as the second best in all locations, except for the Suburbs, where it ranked third.

Customer Spending:

![Customer Gender Dist](https://github.com/user-attachments/assets/64f70938-a164-4973-a8ad-717218856fee)  ![Customer Age Group](https://github.com/user-attachments/assets/df2a793e-fee7-484f-8c33-4fd5101aaad4)

- Female customers account for 54% of total sales.
- Male customers make up the remaining 46%.

The Customer Age Distribution ranged from 18 – 65 years. So, they were grouped into three categories:
Youth = 18 – 39 years old
Middle Age = 40 – 59 years old
Elder = 60 and above.

The Youth category had the highest revenue contribution at 47%, followed closely by the Middle Age at 41%. The Elder group contributed the least at only 13% across all locations.

Stock Management:

![Stock performance](https://github.com/user-attachments/assets/c41e385a-d2db-45d8-91d2-0291fe550ff1)

Looking at the Stock Performance chart above, the most understocked item is Milk, followed by, Iced Tea Bags, Croissant Dough, Muffin Mix and Tea Bags respectively. 

These seem to be mostly the raw materials used in making the products that generate the most revenue, which explains why they are running out faster than the rest. 
The café can improve its Stock management through the following ways:
Using sales data to forecast stock item usage and automate replenishment before key ingredients run out.
Ensuring they have buffer stock for making top-selling products like Muffins, Iced Tea and Cappuccino.

Employee Performance:

![Top !0 Emp](https://github.com/user-attachments/assets/d7c7d3ca-0122-42dd-90cc-720365c529d9)  ![Bottom 10](https://github.com/user-attachments/assets/999351be-dfdd-4875-af77-27fea6cde61e)

The left chart above shows the Top 10 Employees who met or exceeded their sales target. Megan White had the best performance at $11,095, with an average sales target of $2,801.
 
A toggle on the table filter for the bottom 10 performance (right chart) also reveals that Olivia King was the least performing employee at -$9,766 with an average sales target of $3,794.


![Employee Perfomance Average](https://github.com/user-attachments/assets/62284729-fb1e-4e6a-99fd-9f674c2e0b52)

The Average Sales Target for employees was $2,984 (also captured on the KPI section).
Generally, 50% of the employees performed above average, while the other 50% performed below average. 

Furthermore, filtering with the Employee Location slicer reveals the employee locations performing above or below average. Uptown was the least performing location, with more than half (55%) of employees performing below average.

Observation: 
All employees who performed below average, especially the bottom 10, suggest that there might be potential issues in their workplace, which might be tied to a lack of motivation, inadequate training, or being overworked.

Suggestion: 
Their work environment, shift, or work hours, and customer feedback linked to them need to be investigated. A survey can also be sent out to them to understand the root cause of their poor performance.

Customer Feedback:

![Customer Rating](https://github.com/user-attachments/assets/56d3fae8-33d4-49ae-9a11-41c87d58b078)  ![Sentiments](https://github.com/user-attachments/assets/923c036d-7846-4f04-8fb0-f2775c79d550)


From the Customer Ratings chart, majority gave 4 star ratings (217) and 3 star ratings (206) (1 being negative and 5 being positive feedback). Only 199 customers gave 5 stars.

This suggests that generally, satisfaction is decent or average, but there’s room for improvement to turn those 3 and 4 star experiences into 5 star ones, and also find out why a considerable number of them (190 and 188) rated 1 and 2 stars.

Suggestions: 
Feedback from customers who rated 1–3 stars needs to be further investigated to identify recurring complaints that may be a result of slow service, low quality products, e.t.c. 
Loyalty incentives and survey follow-ups for low-rated customers would also be ideal.

The Customer Sentiments indicate that, as much as there seems to be a balance between the three sentiments, the majority of the customers have a Negative experience (344) with the products when compared with those who were Neutral (340) or Positive (316).
This is tied to the Customer Ratings. The observations and suggestions made earlier on the Customer Ratings will directly affect sentiments positively after implementation.






















## 





