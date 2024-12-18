 # Excel-Sales-and-Finance-Analytics-Project-of-AtliQ-Hardwares-Codebasics-

 ## Project objective -

 AtliQ Hardware, a top hardware company specializing in PCs, Printers, Mouse, and Computers worldwide, needs to boost sales and improve net gross margins and Profits.

Now Sales director doesn't just want the reports or Excel files from different regional managers because there are a lot of Excel files and from these reports, potential insights will not come out, so in that case a Data Analyst plays a vital role.

## My Goal as a Data Analyst-
This project tackles analyzing a huge dataset with over million of unorganized sales records, requiring a lot of effort to organize (ETL). The goal is to find important insights to help AtliQ hardware make smart decisions and track key performance indicators (KPIs). The main aim is to make big improvements in how well the company does, especially in net sales and net gross margin.

## Tools & Technique:

Microsoft Excel (v2021)
Power Query
Power Pivot
Pivot Table
Data Modelling
DAX (Data Analysis Expression)
ETL (Extract, Transformation & Load)

𝐒𝐭𝐞𝐩𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝 𝐢𝐧 𝐦𝐚𝐤𝐢𝐧𝐠 𝐭𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐫𝐭

 ## 𝐄𝐓𝐋 (𝐄𝐱𝐭𝐫𝐚𝐜𝐭 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐚𝐧𝐝 𝐋𝐨𝐚𝐝)

i used power query for ETL pocess. loaded extract the csv file to power query , promoted the header 
, corrected the data type , checked the column profiling ,  Ensured there were no missing values, all dimension tables contained a unique column, 
removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot. only keep connection.

using power query craeted blank query and using m code Created a new dim_date table , that includes the date, month, and year in a separate column.
using custom column  i created AtiliQ Hardware Fiscal year column starting from septeber to august end . (financial year of atliq harware )

## 𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠
using power pivot create relationship between dimension and fact tables using star and snowflake schema with one to many relationship.

using DAX language crated calculated measures and column like  net sales (overall and each year like 9 , 20 , 21 ) using aggregate function like sum , calculate , sumx , Divide 



 ## 𝗣𝗶𝘃𝗼𝘁 𝗧𝗮𝗯𝗹𝗲 
Using pivot table summaize the data ,formatting the data , using conditional formating beautify the report for quick analysis . ( net sales for each year and Year over year growth percentage)

### In the sales performance report : 

1) market performance report
2) indian market performance report 
3) Market performance vs Target report 
4) Top 10 products based on the percentage increase in their net sales from previous to recent year.
5) "Division" report
6) Top and Bottom 5 product based on total Qty sold.
7) New launched Product in the year 2021
8) top 5 countries in terms of net sales in year 2021

### In the finance report 
1) Profit and loss by fiscal year 
2) Profit and Loss by month , quarter . 
3) Profit and Loss by Market.
4) Gross Margin % by SubZone


## Task Performed  -
## Project 1: Sales Analysis
Made a detailed report on customer performance. Compared to how well they are doing throughout the years, also are they able to achieve the target or not? This helps Atliq to keep an eye on their customer sales also how much discounts they should give to the customers. Also made a market performance vs target report which helps to understand in which country or market AtliQ doing business well and in which country they don't.

## Project 2: Financial Analysis
Made detailed Profit and Loss (P&L) reports by Year, Month, and Quarter level. Also made P&L reports for different markets. This helps AtliQ understand how they are doing financially, aiding in making smart choices. Clear and helpful reports were created for communicating with stakeholders. It assisted in comparing AtliQ to other companies and in setting up a plan for budgeting and future spending.

Also made a report to analyze Gross Margin percentage (GM%) by Quarters (sub_zone).

Finally made a detailed report to evaluate different things such as the Top 10 Products that are doing very well, Division Level Report, Top and Bottom 5 Products, and Top 5 countries.

## Throughout the journey, I've mastered key skills:

⦁ Leveraging pivot tables for insightful analysis

⦁ Harnessing Power Query to clean up data effectively

⦁ Navigating basic DAX formulas for data manipulation

⦁ Enhancing data presentation with Conditional Formatting

⦁ Elevating the visual appeal of reports

⦁ Deepening understanding of crucial sales metrics

Ultimately, this project is about arming businesses with the tools and knowledge to monitor sales, drive improvements, and seize new growth prospects. By dissecting sales data, businesses can pave their path to success in a dynamic market landscape.


## Overall Insight from sales perfomance report.

1) after analyzing customer performance year , Amazon performance is very good followed by atliq e store and atliq exclusive 
2) from top 5 , India genertaed highest revenue $161.26 million doller followed by usa and south korea.
3) from top 5 product, "AQ Master wired x1 Ms" has highest order 4.15 million followed by "AQ Master wireless x1 Ms" and "AQ Gamers Ms".
4) From the bottom 5 products, "AQ HOME Allin1 Gen 2" has lowest order 9k , followed by "AQ Home Allin1" and "AQ Smash 2".
5) from the new launched products , "AQ Qwerty" generated highest revenue $21.98 million doller followed by  "AQ Trigger
" and "AQ Gen Y".
6) division are like "N & S" , "P & A" and "PC" out of this "P & A" division generated the highest revenue  338.38 million doller.
7) after analyzing the indian market only , amazon and atliq exclusive pefoemance is better 
8) From the top 10 product , "AQ Electron 4 3600 Desktop Processor" has highest growth rate comapare to previous year followed by "AQ Smash 2".

## Overall insight from finance report 
 1)Year 2021 generated $598.88 million doller, which is 204% higher than previous year.
 with having COGS $380.7 million doller in the year 2021 , which is 209% higher than previous year. 
 Generated $218.16 million doller Gross margin in the year 2021 , which is 198% higher than previous year.
 after comparing the gross margin percentage with previous year , GM% in 2021 , 2% lower than the previous year.
2) after analyzing the month wise , Nov and DEC month has highest revenue for all the year , may be becouse of diwali and cristmas.
3) from indian market atliq harware generated the good profit than other.
