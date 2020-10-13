# Assignment7
# Executive Summary
This week we have focused on deleting data from a table using a stored program, how to create a trigger to check the new price of an item in a specific table, and we will practice when to use a event scheduler and when this could be beneficial. 
# Stored Programs
1. For the first task of this week, and trying to delete a customer from the customers table using a stored program I would first start off setting my delimiter to //. Second I would create a procedure called Delete_customer followed by their specific ID number in parentheses. Next we can begin this procedure. Type BEGIN. Then use DELETE FROM customers. Next using a WHERE clause that calls the customers specific ID number. Followed by END. Lastly type out my delimiter. 
2. Creating a trigger named products_before_update. Second call the list_price table from the products table by typing ON products table. 
3. Im not 100 perecent sure if this would be correct for the event scheduler; but to my understanding a situation that an event scheduler could be useful would be in a bakery business would be if we were running a buy 2 get one free sale. This would allow us to check the two most expensive items and give the customer the cheapest one for free. 

# Conclusion
In this weeks lab we have used critical thinking to address problems we may run into such as deleting data, and when to use a event scheduler. We also wrote our first trigger statement that allowed us to only return values higher than 1200 and less than 100 in the unit price category. 
