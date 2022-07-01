# Excel-Sales-Analysis

Case study background: 
Solarify is a well-established manufacturer of solar panels that sells its products in several countries around the world. Recently, their salespeople have started complaining that they are not paid enough for their work. In some cases, this has led to high-performing salespeople leaving the company. Solarify is concerned that this dispute is starting to affect the company’s revenues. 

As Solarify has grown, different regions within the company have set different compensation policies, involving different mixes of salary, commission, and bonuses. The company wants to know how these differences affect performance in different countries. They also want to know if a unified compensation scheme can help optimize performance by improving morale.

You’ve been hired to investigate this problem. You’ll need to use Excel to understand the various compensation schemes currently in use within the company. Can the company develop a single scheme that will be suitable for all? If you solve this problem, the company will be able to hold onto their best sales people and improve their revenues in future years.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

- Step one: Clean the data and set correct number formats.
- Removed duplicates
- TRIM spaces
- Convert numbers stored as text into numbers
- Using find & replace to clean cells
- Using conditional formatting to highlight errors


- Step two: Calculate summary revenue statistics: 
- Total sales revenue and compensation
- Average sales revenue and compensation by sales person
- Revenue, compensation, and compensation as a percentage of revenue by year
- Revenue, compensation, and compensation as a percentage of revenue by country

- Step three: Accounting for different compensation models - using a search panel:
- Total sales revenue, total compensation, and average compensation for a compensation model specified by the sheet’s user - the specified compensation model can be adjusted using a dropdown list. 
- The compensation model, total sales revenue, and total compensation for a country and year specified by the sheet’s user - the specified year and country can be adjusted using a dropdown list. 

- Conclusion: Compensation models that include commission have significantly higher average pay than models that exclude it.

- Step four: Measuring the impact of bonuses and commissions - using a search panel:
- Average compensation, basic salary as a percentage of income, commission earnings as a percentage of income, and bonus earnings as a percentage of income - the specified year and country can be adjusted using a dropdown list. 
- The average amount of commission received by a salesperson under a specified compensation model - the specified compensation model can be adjusted using a dropdown list. 
- The percentage of sales people for a specified compensation model that receive a bonus - the specified compensation model can be adjusted using a dropdown list. 

- Conclusion: Most salespeople eligible for a bonus receive it, but bonuses make up a smaller percentage of income than commissions.

- Step five: Creating Pivot Tables to analyse results:
- Average sales revenue by commission percentage
- Average sales revenue by commission percentage and industry
- Average sales revenue by commission percentage and new/repeat customer
- Average sales revenue by commission percentage and business/consumer customer

- Conclusion: Based on my analysis, I can conclude that the compensation model of a basic salary and commission, with a single rate of commission is likely to be the best choice for Solarify moving forward. 
