# XYZ SUPERMARKETS
XYZ is a large suoermarket outlet with branches in three major cities across the country - Abuja, Lagos and Port Harcourt. The supermarket chain has provided us with data spanning 3 months for us to analyze with the aim of understanding its sales trend and advice on its growth tragectory so as to survive its ever competitive market.


Project Steps
To caery out the analysis, all the necessary and relevant libraries were imported on the jupiter Notebook using pandas. the libraries includes: numpy, pandas, seaborn, matplotlib. etc. The XYZ company project was carried out in the following steps:

## STEP 1
Import the necessary libraries and load the csv files. First combine all the csv files into one. You do this by opening a new folder and saving all relevant files needed in it then type the following lines of code to combine them into one.

## STEP 2: Data Exploration
I explored the data with the following functions:
- .head(): 
- shape:
- Columns attribute:
- describe():
- Missing values:
- info:

## STEP 3
- to_datetime() attribute is to convert the date column to datetime dtype.
- Confirm if the dtype is datetime.
- Converstion of the time column to the appropriate dtype.
- Accurate extraction of Day, Month, Year and Hour features from the date and time columns.
- The unique hours of sales in the supermarket should be accurately determined and the result should be in an array form.

## STEP 4
- Unique count of the categorical columns using value_counts()

## STEP 5
- A groupby function with the 'city' column and aggrevation of sum & mean
- Gross income of the city and also determine the highest total gross income
- Explore unit price, quantity etc.

## STEP 6
- Countplot - Highest sales record
- Countplot - Most used payment method and city with most sales
- Countplot - Highest and lowest sold product line
- Chart should show the product line column on Y - axis and the line parameter for the paymemt column
