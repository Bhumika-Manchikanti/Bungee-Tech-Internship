Question 1:
*first checking the average price of each product.
*we modified the code slightly to fill na values by adding the transform method.
*Then checking the results by comparing the missing values in the price column with the values in the new column.
*Conclusion:The missing value for tomato is filled with 3.12 which is the average value we calculated previously. Similarly, the missing values for cucumber and onion are filled with the correct average value.


Question 2:
*For the products that have a unit of kg, the sales amount values will be the same as sales quantity values.
*For the products that are sold in pieces, we need to extract the kg information from the description and multiply it by the sales amount.
*We can use the where function to update the values conditionally. The weight information can be extracted by using the split function under the st accessor.
*The where function accepts a condition or a set of conditions. We can then assign separate values for the rows that fit and do not fit the conditions.
*Conclusion: The “butter-0.25” weighs 0.25 kg. In the last row, the sales quantity is 36 so the sales amount needs to be 0.25 * 36 which equals 9.



Question 3:
*Select only the Goal column.
*Viewing only the columns Team, Yellow Cards and Red Cards and assign them to a dataframe called discipline
*Sorting the teams by Red Cards, then to Yellow Cards
