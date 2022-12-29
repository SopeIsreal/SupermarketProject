# XYZ SUPERMARKETS
XYZ is a large suoermarket outlet with branches in three major cities across the country - Abuja, Lagos and Port Harcourt. The supermarket chain has provided us with data spanning 3 months for us to analyze with the aim of understanding its sales trend and advice on its growth tragectory so as to survive its ever competitive market.


Project Steps
To caery out the analysis, all the necessary and relevant libraries were imported on the jupiter Notebook using pandas. the libraries includes: numpy, pandas, seaborn, matplotlib. etc. The XYZ company project was carried out in the following steps:

## STEP 1
Import the necessary libraries and load the csv files. First combine all the csv files into one. You do this by opening a new folder and saving all relevant files needed in it then type the following lines of code to combine them into one.

## STEP 2: Data Exploration
I explored the data with the following functions:
- .head( ): Shows the first few lines of the table so as to have an idea of what the data looks like
- shape: Shows the number of rows and columns in the data frame
- Columns attribute: lists the names of the columns
- describe( ): Gives a statistical summary of all the colums in a data frame
- Missing values: Using isnull( ) shows that there arent any missing values
- info: gives information about total column number, column name, dtype, total number of rows

## STEP 3
- to_datetime( ) attribute is to convert the date column to datetime dtype.
- Confirm if the dtype is datetime.
- Converstion of the time column to the appropriate dtype.
- Accurate extraction of Day, Month, Year and Hour features from the date and time columns.
- The unique hours of sales in the supermarket should be accurately determined and the result should be in an array form.

## STEP 4
- Unique count of the categorical columns using value_counts( )

## STEP 5
- A groupby function with the 'city' column and aggrevation of sum & mean
- Gross income of the city and also determine the highest total gross income
- Explore unit price, quantity etc.

## STEP 6
- Countplot - Highest sales record
- Countplot - Most used payment method and city with most sales
- Countplot - Highest and lowest sold product line
- Chart should show the product line column on Y - axis and the line parameter for the paymemt column

## INSIGHTS
Interpretation of values
- Mean: The average unit price across all the stores is N20,041.96 (this is exclusive of tax), while the average quantity sold is approximately 6 units (5.51 units). A   sum of N5,536.57 is the average amount paid as 5% tax fee for customer buying. The average total price of goods i.e. including tax is N116,268.03. The average amount   of cost of goods sold spread across the three stores is N110,731.45. The average gross margin percentafe is 4.76%, while the average gross income is N5,536.57.         Customers gave an average satisfaction rating 6.9% across all three stores
- Std (Standard deviation): The standard deviation tells us how far apart other figures are in relation to the mean. A high standard deviation means that the figures     are spread out while a low standard deviation means that figures in the data are clustered around the mean. In relation to the unit price, the standard deviation is   high at N9, 538.06 while the mean is at N20,041.96. The standard deviation of the quantity is not too high at 2 units in comparison to the mean at 5 units. The         standard deviation of the tax is low in comparison with the mean. They are closely clustered together. The standard deviaton of the total price of food N88,518.72     which includes tax in its summation, is high when compared to the mean of N116,268.03.
- Min: The minimum price per unit of goods sold across the three stores is N3,628.80. While the minimum quantity sold is 1 unit. The minimum amount of tax paid is       N183.06. The minimum cost of goods sold is N3,661.20.
