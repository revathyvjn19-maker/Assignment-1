# Assignment-1
## Data Exploration
# Question No1
-Total price of all products 
**=SUM(D2:D35)2**
- How many products are there in the dataset
**=COUNT(D2:D35)**
- Average price of the products
**=AVERAGE(D2:D35)**
# Question No2
- Minimum price among all products.
**=MIN(D2:D35)**
- Maximum price among all products
**=MAX(D2:D35)**
# Question No 3
- Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
**IF(D2>=500,"High Price","Standard Price")**
# Question no 4
- Total price for products in the 'Electronics' category
**=SUMIF(F2:F35,"Electronics",D2:D35)**
- Count of products with a price less than $100
**=COUNTIF(D2:D35,"<100")**
# Question No 5
- Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function
**=LEFT(A2,2)**
- Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
**=RIGHT(A2,2)**
- Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
**=MID(A2,4,3)**
