# Vending-Machine-Analysis
An analysis of 2022 vending machine sales data of 4 vending machines in different locations in New Jersey, US. This analysis aims to identify potential ways to reduce waste, maximize sales/ profit.  


## Project Overview
This project aims to identify insights from historic vending machine data to drive decision making for personal vending machine businesses.  
Optimise vending machines, if I were to spend x dollars with certain constraints, how would I optimise this?

## Questions
1.	Which category of product has the most sales? 
2.	Which location has the highest sales?
3.	Is the location with the highest sales densely populated? What are the socioeconomic description is the population there?
4.	Does 2023 or 2022 sell more products? Do we expect an increase in sales year on year?
5.	Which product is the most popular?
6.	Do people prefer to buy with cash or credit card? 
7.	Which machine has the highest sales? Is it nearing an entrance or popular shop?

## Data Sources
Kaggle.com Vending_machine_sales Dataset

## Tools
•	Excel - Data Cleaning  
•	PowerBI - Creating Reports

## Data Cleaning/ Preparation

 Figure 1 Before
![image](https://github.com/hsydata/Vending-Machine-Analysis/assets/162429657/905ab645-714c-4de9-bfee-0e31ba331d5d)

 In the initial data preparation phase, we performed the following tasks:
1.	Data loading and inspection
2.	Deleted or modified missing values
3.	Removed unnesecary columns 
4.	Data cleaning and formatting

Figure 2 After
![image](https://github.com/hsydata/Vending-Machine-Analysis/assets/162429657/5033c51c-4e02-4759-b8a2-b202b44f5196)


## Exploratory Data Analysis
We involved exploring the sales data to answer key questions, such as:
1.	Which category of product has the most sales? 
2.	Which location has the highest sales?
3.	Is the location with the highest sales densely populated? What are the socioeconomic description is the population there?
4.	Does 2023 or 2022 sell more products? Do we expect an increase in sales year on year?
5.	Which product is the most popular?
6.	Do people prefer to buy with cash or credit card? 
7.	Which machine has the highest sales? Is it nearing an entrance or popular shop?

## Results/ Findings
The analysis results are summarised as follows:
1.	Food had the most profitability, making up 54.4% of the sales of vending machines. 
2.	GP and Public library had the highest sales, doubling the sales of the vending machine in the shopping mall. 
3.	Assuming the geographical location of these vending machines are relatively close to each other, we assume the population the be the same, and no difference to the socioeconomic between the customers of these vending machines. 
4.	The data seems to be yearly data, we can only study throughout the year 2022. We see the sales peak in the midyear ($2000- 2500 in sales), and are lowest around the start and end of the year ($1500 in sales).
5.	We see that drinks are the most popular, being monster energy, coca cola, red bull and spring water. Kitkat is also highly sold. 
6.	We see a roughly equal amount of customers using cash as card.
	![image](https://github.com/hsydata/Vending-Machine-Analysis/assets/162429657/db4423bc-dfdd-47ae-b74b-83c2208103b9)

 
## Recommendations
Based on the analysis, we recommend the following actions:
*Assumptions to this problem: 
- Our capital is constant, 4 vending machines.
- each vending machine has 4x3 big slots +8x3 smaller slots. 
- Cost and profit for a given product within a category are approximately the same. *

1.	We recommend keeping the all the categories of food. However, we suggest stocking on high selling products, coca cola, monster energy, red bull, spring water and kit Kats. These products tend to be well known products, stocking with other well known may do well. 
2.	Public library doubled in sales vs square mall, suggest looking into costs for repositioning poor performing vending machines to public libraries. *Costs of rent space, transportation costs etc to be considered* 
3.	We suggest looking into investing more into additional vending machines during the middle of the year or reducing the number of vending machines near the start of the year. 
4.	We recommend keeping both cash and card payment options available. 


## Limitations
The limitations of this analysis is as follows: 
- Data is limited to 1 year, insights are unlikely indicative of the performance across multiple years, nor predictive of the upcoming periods. 
- Data collected is only for 4 vending machines.  
- The data has daily granularity. Hourly data may aid in determining popular purchase times, for restock prescriptions.  

## Improvements
The possible improvements to be made:
1)	Trouble with converting the location column into a location datatype, to use as a map. 
2)	We can structure the final dashboard more nicely, using uniform colour palette, sizing of graphs, etc. 
3)	Can use SQL code to transform the data/table instead of Excel. 
4)	Can use graphs to filter. Can alternatively add slicers for months, products and locations, to know what are popular by location.
	
** Personal Improvement Notes
1.	Slicers
2.	High level on dashboard. 
3.	Detailed on pg 2 / subsequent pages. 
4.	Identify dimensions 
5.      Start to implement KPIs

## Personal Improved Dashboard
#### High Level Summary Dashboard 
![image](https://github.com/hsydata/Vending-Machine-Analysis/assets/162429657/2248831c-9d5b-4f87-b468-bbd2a712fa48)

#### Product Detail Dashboard 
![image](https://github.com/hsydata/Vending-Machine-Analysis/assets/162429657/bbdec508-b864-4c57-a807-90a186478954)

** The data is basic, would like to in future use star schema and make other detailed dashboards for location and catagory. 





## References
1.	Stack Overflow

