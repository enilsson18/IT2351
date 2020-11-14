i. Executive Summary
In this assignment, I created 2 stored procedures and 1 stored function. In addition, I dealt with custom error reporting and handling, parameters in functions, declaring variables, and if statements. 

ii. Stored Programs
1. For the first stored procedure, I made one called ProductCount which returned whether the number of products in the products table was gretaer than or equal to 18. First I made the basic outline of a generic stored procedure and filled in my values for the names. Then I made the declare statement for the count. Then I made the output if and else statements along with their text. Finally I wrote a select into statement using the aggregate function "count()" to find out how many products were in the table. At the very end I wrote a simple test script to call the procedure.

2. The second stored procedure was called InsertCategory which tried to insert another category into the categories table with the value "Guitars". If there was a duplicate in the table then it would return a custom error message and it would return a custom success message if it worked aswell. I started by making the outline bare bones for a stored procedure and then made the insert statement with an auto increment function for the id by adding 1 to the current length of the categories table. Then I made the error reporting variables and continue error handler. Finally I made the error reporting if and select statements at the bottom of the function. At the very end I wrote a simple test script to call the procedure.

3. The Final script I wrote was a stored function. It would take in the item_id of an item in the order_items table and would return the price of an item with the discounted amount already subtracted from it. The function was called discount_price. I started by making the normal outline of a stored function and then filled in the parameter. I stated the return data tyle and that it would read sql data. I then made a variable to store the result in and used a select statement to find and subtract the discount amount from the original price. Finally I made a test script at the bottom to try out the function which showed both the price and discount amount, followed by the functions result.

iii. Conclusion
I learned a lot about the structure of sql based procedures and functions through this. I have noticed that my use of basic sql commands is getting much faster and more fluid. I like the assignment aswell because I mainly use C based code so functional logic is much easier for me to pick up than some of the wierd things we have done with sql result tables like rollups. I feel very confident in my abilities with stored procedures and functions.