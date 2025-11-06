# CAR-SALES-REPORT
I currently work on the accounting side of a dealership, one specific brand too.  I think it'll be interesting to see the sales of other car brands too!

Here is the link of the dataset from Kaggle. 
https://www.kaggle.com/datasets/missionjee/car-sales-report

##**Dataset Overview**
This dataset was found on the Kaggle website, "Car Sales Report".  It shows 23,906 different vehicle transactions and includes information about the vehicles themselves & customer demographics.  For the vehicles, it shows the ID, make, model, color, engine, transmission, body style, amd the price.  For the customer info they included the name, gender, and phone number. It also includes the dealership name & the region where they are located.


##**Started the Analysis**
To start the analysis, I made an introduction to have readers understand the dataset & why I chose it.  Since I do work at a dealership, I want to see other vehicle transactions from around the country.
I imported all the libraries necessary to perform the analysis.  I imported the dataset and displayed the top rows with the '.head()' function just to get an overview of what I would be working with


##**Cleaned the Data**
After importing the data, I used the '.info()' function to see if my dataset had any null values.  Out of the 23,906 rows of data, luckily there was only one row that was missing the customer's name.  To make this analysis as clean as possible, I decided to drop that whole row.  I dropped it because it was only one & it wouldn't affect any analysis.  While cleaning the data, I also checked for duplicates and found that there wasn't any. 


##**Data Manipulation**
Once the data was cleaned, I performed some data manipulation to help me get some more insights of the data.
I first sorted the data to show me the top 5 highest priced vehicles.  Out of those five, four of them were Cadillace Eldorados.
I then sorted the data by annual income in ascending order to show me the lowest income.  Andy, the customer with the lowest income was able to purchase am Infiniti I30.
Finally, I grouped the data by the make and price, to show me what companies make the least expensive vehicles.  This showed me Hyundai makes the least expensive vehicles.

##**Data Visualizations**
I created three visualizations to highlight customer demographics, pricing, and vehicle preferences.

#Gender of the Customers
<img width="510" height="359" alt="image" src="https://github.com/user-attachments/assets/33c94894-993b-4138-8c08-2be58271bd76" />
