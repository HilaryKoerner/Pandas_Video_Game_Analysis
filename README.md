# Heros of PyMoli Video Game Analysis

Using a raw CSV file from a video game company and pandas, I created various anlysis based on demographics and purchasing information.  

1. I found the total number of unique gamers and created a data frame. 
2. I analyzed each individual purchase and found the number of items available for purchase, average purchase price, number of purchases, and total revenue. 
3. To analyze the data based on gender, I made a simple data frame of all unique players grouped by gender. I found the total count and percentage based on gender.  
4. I created a data frame based on gender and purchase analysis. I split the total of all purchases, average purchase price, and total purchase value by gender. Then I found the avergage total purchase per person (removed duplicate screen names) and split by gender. 
5. To analyze the data based on age range, I created bins by age range and added this as a column to the original data frame. I removed duplicate screen names, found the total count and the percentage of players, and grouped the findings by age range. 
6. I used the data frame based on age range and analyzed the purchases. I split the total of all purchases, average purchase price, and total purchase value by age range. Then I found the avergage total purchase per person (removed duplicate screen names) and split by age range.
7. To find the top spenders, I created a data frame based on unique screen name. This included number of purchases, average purchase price, and total purchase value for each player. I sorted the data frame by highest purchase value for each player. 
8. To find the most popular item, I created a new data frame grouped by item ID and item name. I found the purchase count, item price, and total purchase value for each item. I sorted this by highest purchase count. 
9. ![popitems](https://user-images.githubusercontent.com/74504885/122325218-cacefb00-ceef-11eb-8728-db0d18210be6.PNG)
10. To find the most profitable item, I used the same data frame grouped by item ID and item name and sorted the purchase count, item price, and total purchase value for each item by highest Total Purchase Value. 
11. ![pymoli_profitable](https://user-images.githubusercontent.com/74504885/122325108-94917b80-ceef-11eb-97b6-6ea97939be9e.PNG)


From this analysis, I am able to observe three things. 
1. Although men make up the majority of purchases, women have a higher average purchase price. 
2. Although the 20-24 age range users make up the majority of purchases, 35-39 users have a higher average purchase price. 35-39 year old users only make up 5.3% of user though, so I would not shift marketing towards them. 
3. The price of the most popular item is above the mean so item price may not affect purchasing decisions. 
