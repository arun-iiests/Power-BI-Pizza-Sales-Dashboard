# Power BI Pizza Sales Dashboard

## Project Overview

The Power BI Pizza Sales Analysis Dashboard offers a concise snapshot of crucial sales metrics. Key performance indicators (KPIs) such as total revenue, total pizza sold, total orders, and average pizzas per order are prominently featured. Temporal trends are visually presented through monthly and daily trend charts, providing a dynamic view of sales patterns over time. Sales distribution across categories and pizza sizes is effectively communicated using donut charts. The dashboard goes further to provide insights into the top and bottom-performing pizzas based on revenue and order quantities. This compact yet powerful tool empowers decision-makers with actionable insights, facilitating strategic planning and informed decision-making.

Embarking on my inaugural Power BI project has been an immensely enlightening experience. Working with a real dataset has not only provided practical insights but also made the journey truly exhilarating. The various processes involved have contributed significantly to my learning curve. The key takeaways from this endeavor include...

## About Dataset
"This dataset captures comprehensive information on pizza orders. Each entry includes a unique 'pizza_id' and 'order_id' for tracking individual pizzas and orders, respectively. 'pizza_name_id' links pizzas to specific names, while 'quantity' denotes the number ordered. Date and time of orders are recorded in 'order_date' and 'order_time.' Pricing details include 'unit_price' and 'total_price.' Pizza attributes such as 'pizza_size,' 'pizza_category,' and a list of 'pizza_ingredients' are specified, along with the distinctive 'pizza_name' for each item."


Shape Of dataset: (38811, 12)

## Data Cleaning and Transformation
1. Transformed Pizza_size column
   |From|To|
   |-------|------|
   |S|Small|
   |M|Medium|
   |L|Large|
   |XL|X-Large|
   |XXL|XX-Large|
2. Extraction of Day & Month Name from Date
3. Adding conditional column (Day number)

## Data Analysis And Visualisation 
1. KPIs For total revenue,Avg order value, total pizza sold, total orders, and average pizzas per order
2. Column chart for Total order by order Day
3. Area chart for Total order by month
4. Donet Charts for % sales by pizza category and size
5. Funnel Chart for Total pizza sold by category
6. Slicer- Vertical dropdown for pizza category
7. Date Slicer
8. Bar charts for top and bottom 5 pizzas by revenue, total quantity and total orders
9. Buttons for Page Navigation



## My Key Learnings
1. Writting Basic DAX Functions fro creating measures
2. Adding Images
3. Applying Conditional color esp. gradient colors
4. Sorting Day name as per week day sequence by adding the coonditional column
5. Page navigation
