# IMPACT OF DISCOUNT STRATEGY ON SALES PERFORMANCE AND CUSTOMER RETENTION (JANUARY 2025 VS JUNE 2026)

### DESCRIPTION
Impact of Discount Strategies on Sales Performance, Customer Retention, and Profitability: A Case Study of Exco Shopping Mall. This project was carried out extensively with MS Excel and Power Query.

<br>

## TABLE OF CONTENTS 
- OBJECTIVE
- DATA SOURCE
- STAGES
- DESIGN
    - Mockup
    - Tools
- DEVELOPMENT
    - Pseudocode
    - Data Exploration
    - Data Cleaning
    - Transform the Data
- TESTING
    - Data Quality Tests
- VISUALIZATION
    - Results
    - DAX Measures
- ANALYSIS
    - Findings
    - Validation
    - Discovery
- RECOMMENDATIONS
    - Potential ROI
    - Potential Courses of Actions
- CONCLUSION

<br>


## OBJECTIVE
<ins>What is the key point?</ins>
The Head of Sales wants to find out how the discount introduced this year (2026) affected sales. And wants to know if the discount has been effective or should be removed.
<ins>To build a dashboard that shows the impact of the discount, it’ll include;</ins>
-	Total sales after vs before
-	Profit before vs after
-	Discount amount
-	Customer type

<ins>USER STORY</ins>

The Head of Sales at Exco Shoppin Mall introduced discount to purchases in January 2026 with the aim of increasing sales and retaining customers without tightening profit much.  Now, he wants to find out;

    - Did introducing discounts increase sales Performance?
    - Did discount improve customer retention?
    - What discount range generated the highest profit?
    - Which product categories benefited the most from discount?

With the sales record available (from Jan 2025 – June 2026), we’re going to use the discount given, sales recorded, profit generated and customer type. And we will compare the record from when the discount was introduced (Jan 2026) till date (June 2026) with previous record (Jan 2025 – Dec 2025).

## DATA SOURCE

What is needed to achieve our objective? This will determine our data source.
Since it is within the company, we will need the company’s Sales Data (Sales Record) that includes:

- discount given to customers
- sales recorded
- profit generated; and
- customer type

The data source is a first party data generated from ChatGPT.

## STAGES
    1.	Design
    2.	Development
    3.	Testing
    4.	Analysis

<br>

## DESIGN
<ins>Dashboard components</ins>

What should the dashboard contain based on the requirements provided? 
To understand what it should contain, we need to figure out what questions we need the dashboard to answer:
- Did discounts increase sales? 
- Did discounts improve customer retention? 
- Which products benefited most from discounts? 
- Which customer segment responded best? 
- Did profits rise or fall? 
- What discount range produced the best balance between sales and profit?

<ins>Dashboard Mockup</ins>
- Monthly Sales (Line Chart) 
- Stores (Clustered Column)
- Sales by Product/Category (Horizontal bar Chart)
- Top 10 products (Horizontal bar Chart)
- Brand or Category contribution (Doughnut Chart)
- Discount Cat (Pie Chart)
- Customer Retention rate (Column Chart)

<ins>Tools</ins>

Microsoft excel was used to;
- Explore the data
- Clean, test and analyze the data
- Visualize the data via interactive dashboards

GitHub was used to host the project.

<br>

## DEVELOPMENT
<ins>Pseudocode</ins>
1.	Get the data
2.	Explore the data in Excel
3.	Clean the data with Excel
4.	Test the data with Excel
5.	Visualize the data
6.	Generate the findings based on the insights
7.	Write the documentation + commentary
8.	Publish the data to GitHub Pages

<ins>Data Exploration notes</ins>
- It contained 3,618 rows with 29 columns.
- The customer ID matches each customer’s name so it won’t be needed and will be removed.
- The city column is not necessary since the store names are already here, likewise the payment and year column.
- Each store has only one salesperson per store.
- A new column,” Net Profit”, will be inserted to show the net profit, which is the deduction of discount amount from the profit.
- Another column (Year Half) was inserted to show what each half of the year had to show since the year we’ll be looking into is the first half of this year. We have to compare it with last year’s first half to avoid getting a wrong analysis.
- We tried to understand the “Purchase Type”, “Days since last purchase” and “Customer Retention” column as it’ll play a key role in finding how discount affected the retention of customers.




<br>




