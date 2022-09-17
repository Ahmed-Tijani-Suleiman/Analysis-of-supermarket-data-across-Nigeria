# ANALYSIS OF SUPERMARKET DATA ACROSS THE COUNTRY FOR COMPANY XYZ.
## Step 1 - Loading Datasets
 - Correct use of pathname pattern - glob
 - Combine all the files generated in a list and export to a CSV.

## Step 2 - Data Exploration
 - creaye a copy of the dataframe for cleaning.
 - Use the head() method to view first few rows of the dataset
 - Check the number of rows and columns present in the data using the shape attribute.
 - Generate the names of the columns using the columns attribute.
 - Use describe function to generate the statistical summary of the dataframe
 - Use meaningful sentences to describe findings from the data statistical summary
 - Use of correct method to check for Missing values
 - Check for duplicates.
 - Check the information of the DataFrame using the info method.

## Step 3 - Dealing with DateTime Features
 - Use to_datetime() to convert the date column to datetime
 - Check the datatype to confirm if it's in datetime
 - Accurate conversion of the time column & prints appropriate data type
 - Accurate extraction of the Day, Month, Year & Hour features
 - The numbers of unique hours of sales in the supermarket are accurately determined.
 - Result that shows an array that contains the unique sales hours.

## Step 4 - Unique Values in Columns
 - Appropriate method to generate the unique values in the categorical columns.
 - Generated the count figure of the categorical values using the value_counts() method.

## Step 5 - Aggregation with GroupBy
 - A groupby object with the "City Column", and aggregation function of sum and mean.
 - A table that shows the gross income of each city, and determines the city with the highest total gross income.
 
## Step 6 - Data Visualization
 - generate a distplot of the quantity of goods purchased.
 - Appropriate use of countplot to determine the branch with the highest sales record.
 - Appropriate use of countplot to determine the most used payment method & city with the most sales.
 - To determine the gender that spends most for each city.
 - to determine the product line females in port harcourt spends the most on.
 - Appropriate use of countplot to determine the highest & lowest sold product line.
 -  To determine the branch with the lowest rating.
 -  To determine the product line each gender spends most on in the supermarket.
 - 7 day Moving average for gross income.
## Step 7- Insights.
 From the visualization charts it is observed that:
  - The Lagos Branch has the most sales.
  - Males spend more in Abuja and Lagos, while Females spend more in Port Harcourt
  - The most used payment method for the supermarket is E-pay.
  - The most used Payment Method for the branch A, B is E-pay while C is Cash.
  - On the Average Females Spend more on all product Line except Sports and Travel, Health And Beauty.
  - On the Average Males Spends more on expensive product lines except for Food and Beverages, Home and Lifestyle.
  - The Unit Price, Quantity, Gross Income, Total, cog are positively correlated.
  - The time with the most sales in the Supermarket is 7Pm.
## Future Work
  - Working with a data set that will require the application of data cleaning techniques.
  - Apply machine learning models to get more information and to make predictions.
## Stand Out Section
  - Checking the correlation between variables and visualizing using heatmap().
  - Checking the Spread of the Quantity of goods bought.
  - To determine the gender that spends more for the cities
  - To determine the product line each gender spends most on for the cities.
  - Checking if the customer type influences sales.
  - To determine the Peak sales hour.
  
