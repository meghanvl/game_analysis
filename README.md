# game_analysis

## Option 1: Heroes of Pymoli

![Fantasy](Images/Fantasy.png)

Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. 
You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. 
As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

### Player Count

* Total Number (value counts) of Players

### Purchasing Analysis (Total)

* Number of Unique Items (len and .unique)
* Average Purchase Price (.mean)
* Total Number of Purchases (value counts)
* Total Revenue (sum)

### Gender Demographics

* Percentage and Count of Male Players (count male players/total)
* Percentage and Count of Female Players (count female/total)
* Percentage and Count of Other / Non-Disclosed (count other/total)

### Purchasing Analysis (Gender)

* The below each broken by gender (group by?)
  * Purchase Count (value counts)
  * Average Purchase Price (total purchase amount .mean)
  * Total Purchase Value (value counts ?)
  * Average Purchase Total per Person by Gender (group by gender ?, gender total/ total purchase)

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value
