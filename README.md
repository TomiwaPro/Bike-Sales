# Bike Sales Analysis

### Project Overview

This data analysis project aims to provide insigts into the sales performance of a bike company over the past years, from 2011-2016. By analyzing various aspects of the sales dats, we seek to identify trends, make data-driven recommendations, and gain deeper understandingg of the company's performance.

### Data Source

The primary dataset used for this analysis is the 'sales.csv' file, containing detailed information about each sale made by the company. I got the dataset from Kaggle, [Find Here](https://www.kaggle.com/code/sadiqshah/bike-store-sales-in-europe/input?select=Sales.csv)

### Tools
- Excel - Data cleaning and transformation
- Excel - visualization

### Data Cleaning
Before I start cleaning the data I created another sheet named 'Working Sheet', this is where the data cleaning and transformation will take place and the reason for creating another sheet id to retail our raw dataset incase there is loss of data during data cleaning or others we can easily go data to our raw data without disturbing our client for the same dataset, it is more like a backup plan for the dataset.

- Removing Duplicate

To remove the duplicates in the data I use the 'Remove Duplicate' function which remove the duplicates. The initial number of rows we have is 113,037, after apply the function we now have 112,037 rows.

### Data Transformation

- Renaming column value

The customer Gender is 'M' and 'F', I'm going to rename them for ease understanding, 'M' as 'Male' and 'F' as 'Female'. This is achievable by the 'Replace All' function in Excel.

Now the data is ready for visualization, we have 18 columns and they are all in the right format.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- Sales Analysis:

What is the total revenue generated each year?

Which month had the highest sales revenue in the past year?

Identify the top 5 best-selling products by revenue.
- Customer Demographics:

What is the average age of customers for each product category?

How many customers are there in each age group?
- Profit Analysis:

Calculate the total profit for each product category.

What is the average profit per order?
- Geographical Analysis:

Which country has the highest total sales?

Provide a breakdown of sales by state.
- Product Performance:

Calculate the total order quantity for each sub-category.

Determine the product with the highest order quantity.

What is the average unit price for each product category?
- Cost and Pricing Analysis:

Calculate the total cost for each product category.

Determine the average unit cost and unit price for each sub-category.

Identify any products where the unit cost is greater than the unit price.
- Customer Behavior:

Analyze the purchasing patterns of male vs. female customers.

Determine the most common age group for each product category.

### Dashboard

Before we could visualize we need to create pivot table for each questions to be answer, I also create a sheet 'Pivot Table' for this. In this sheet I create all the pivot tables needed for the question to be answered through the dashboard.

After I'm done with the pivot tables, I added another sheet named 'Dashboard' to visualize the pivot table created.
- I added a slicer for Country and State, so that user/client can easily choose preferred Country(s) or State(s) to explore.

#### Sales Analysis

![Sale Analysis](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/4d06f6c5-6898-440c-bf38-57451ee94118)

#### Customer Demographics

![Customer Demographics](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/023a733f-cd8f-45f5-bfd1-eeb3ca2eeaa8)

#### Profit Analysis

![Profit Analysis](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/45f80513-1dd0-47be-aa0e-dd35d9267326)

#### Geographical Analysis

Here I create another slicer for Total Revenue by State for easy navigation and for the value to readable because we have alot of State. Note: This slicer only work for 'Total Revenue by State'.
![Geographical Analysis](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/2f7f8a45-0844-4ffd-a2b6-f2ac9a8a2faf)

#### Product Performance

![Product Performance](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/416b2942-66b1-4099-944c-3540783ea675)

#### Cost and Pricing Analysis

I also create a slicer for Total Cost and Total Price by Product Sub-Category for easy navigation and for the value to readable because we have alot of Product Sub-Category. Also this slicer only work for 'Total Cost and Total Price by Product Sub-Category'.
![Cost and Price Analysis](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/2c95ca65-ea07-4f61-af48-e7caf837fd77)

#### Customer Behavior

![Customer Behaviour](https://github.com/TomiwaPro/Bike-Sales/assets/160256704/2c36d445-6256-4a02-b4e9-a0a3b8a7fce6)

With this dashboard we can answer the questions even more question easily by using the sicer to select the Country and state we want to anlysis or explore. 
[Sales.csv](https://github.com/user-attachments/files/15858828/Sales.csv)
