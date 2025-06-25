# lithia-motors-car-sales-overview-2022-2023-
The project will help the car dealers identify areas for improvement and potential growth especially across monthly sales , understanding consumer behavior based on car colour body style choice and, enhancing sales strategies and offering actionable insights for manufacturers and dealers.

![DASHBOARD 10 a](https://github.com/user-attachments/assets/e26078f6-1d20-42c5-9909-3e13347a6a28)

![DASHBOARD 10 b](https://github.com/user-attachments/assets/c6d6e085-9391-43ad-bbd4-10d85f5eee7c)

INTRODUCTION

The automobile industry is a very dynamic pivotal sector, reflecting consumer preferences, economic trends, and technological advancements. This report provides an insightful analysis of car sales performance across all regions were Lithia motors inc. is situated, exploring key metrics such as regional sales distribution, sales by car companies,colour, car transmission and engine preferences while understanding the correlation between the purchasing power of customers based on their annual income capacity.

OBJECTIVES

To proffer actionable insights ,the following need to be examined;

Monthly sales trend across 2022-2023
Weekly sales performance
Regional sales distribution
Customer sales analysis
Sales by car companies and top selling car models
Customer choice on car body style and colour
Most sold car engine type and car transmission type
Gender purchase distribution

METHODOLOGY

The dataset was imported into power Bi and power query was used to transform the data. The columns were formatted individually to the specific data type contained in the individual rows and mostly from the date columns. In the Engine column,some special character were noticed an cleaned for effective readability and visualization. For effective analsis, DAX was used to introduce calculated columns WEEKDAYS and MONTH. This was done to be able to analyze the weekly and monthly sales ditribution.

For the weekday,this formula was used=format('car sales'[Date].[Date],"ddd") This was used to ascertain the weekly sales distribution across regions

For the month option, this formula was used= format('car sales'[Date].[Month],"mm") This was used to ascertain the monthly sales distribution across regions

KEY INSIGHTS

Lithia motors made their best car sales in the December month generating $99M across all regions while the made the least in the February month generating $21M across all regions

Customers preferred buying cars on Tuesdays more during weekdays in Lithia motors. They least buy cars on Thursdays

Among all regions, only the Austin and Janesville regions made sales above the average regional sales $96M with the Scottsdale region making sales exactly $96M. The Austin region generated the highest revenue totaling to $117M
The customer Emma(male) patronized Lithia motors more than any male customer while Emma(female) and Alexis(female) patronized the highest from the female customers

Lithia motors made more sales in the year 2023 more than 2022 with an 80% increase

The best car model is the Lexus LS400
The most sold car company cars are from Mistubushi particularly Montero sport making most sales

Pale white cars are mostly purchased

SUV cars are mostly purchased with Hatchback cars following up. The least purchased car body style purchase was the Hardtop
Customers mostly go for Automatic transmission cars
Double overhead camshaft engine cars are mostly purchased

KEY OBSERVATIONS

Monthly & Yearly sales trend across 2022-2023

![image](https://github.com/user-attachments/assets/d9b00825-2246-485d-aa94-1f8c1ab4d711)

