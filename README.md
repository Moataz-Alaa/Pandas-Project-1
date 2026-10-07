# Pandas Practice Task
---------------------------------------
Use the provided products.csv file.

1. Read the CSV file into a pandas DataFrame and print it.

2. Display the first 5 rows of the DataFrame.

3. Display the summary statistics of the DataFrame.

4. Display the data types of each column of the DataFrame.

5. Filter: Display only the products where Price > 5000 or Rating > 4.5

6. Sort: Sort the products by Price in descending order.

7. Handle Missing Values:
    1. Check for missing values in the DataFrame.
    2. Fill missing Price values with the average price.
    3. Fill missing Stock values with the average stock.

8. Add a new column: Add a column called In_Stock that is True if Stock > 0, otherwise False.

9. Add a new column: Add a column called Total_Value that contains Price * Stock.

10. Filter: Display products where Price > 3000 and Rating >= 4.0.

11. Aggregation: Calculate the average, minimum, and maximum Price, and total Stock.

12. Add a new column: Add a column called Price_Category:

    * Expensive if Price >= 10000
    * Medium if Price >= 3000
    * Cheap if Price < 3000

13. Rename a column: Rename Product_Name to Name.

14. Remove a column: Remove the Product_ID column from the DataFrame.

15. Drop Duplicates: Check for duplicate rows and remove them from the DataFrame.

16. Sort: Sort the products by Rating in descending order.

17. Save the modified DataFrame to a new CSV file called products_modified.csv.