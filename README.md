# MLB Beer Analysis
![Baseball](https://user-images.githubusercontent.com/60836219/154823843-7b09613d-542b-42bd-bacb-ce4732e8d0c4.jpg)

## Introduction
The data set contains information on the beer prices for 30 baseball teams for 2013, 2014, 2015, 2016, and 2018. It has a column for the year, team, nickname, city, price, size, and price per ounce.

This analysis aims to see if the same baseball team will consecutively have the most expensive beer, least expensive beer, most expensive beer per ounce, or least expensive beer per ounce. I hypothesize that some baseball teams will consecutively have the most expensive beer or least expensive beer.

### Connection and Data Cleaning
The first thing I had to do was connect to my Microsoft SQL Server Management Studio. Once I had a successful connection, I selected the table I needed to view in my Jupyter Notebook. I viewed the data types of the data set and changed them to the correct data types. There were 5 rows removed from the data set because it contained information that was unnecessary in this analysis. Once I finished cleaning the data set and set it up how I wanted it to be, I filtered the data set by the years and made copies of each year. I ended up with 5 data sets, each containing only information from a specific year.

Before Cleaning

![Before Cleaning](https://user-images.githubusercontent.com/60836219/154824711-d7ab7289-d194-4eeb-b9c5-32a0f9f31270.PNG)

After Cleaning

![After Cleaning](https://user-images.githubusercontent.com/60836219/154824713-c4edaa38-69f5-4ae6-a3ac-fb23741295a1.PNG)

### Analysis

![Beer Price 2018](https://user-images.githubusercontent.com/60836219/154824399-5ea3d7b2-d1ec-46c3-aa57-b56484005a08.png)

The exciting findings I found is that only in 2014 and 2015, Miami Marlins were the baseball team with the most expensive beer, but different groups had the most expensive beer in the other year. The Arizona Diamondbacks were the baseball team with the least costly beer in 2013, 2014, and 2015. The Colorado Rockies were the baseball team with the least expensive beer in 2016 and 2018. This is very interesting because it seems it is more common for the same baseball team to have the least expensive beer consecutively than the most expensive beer consecutively.

![Beer Price per Ounce 2018](https://user-images.githubusercontent.com/60836219/154824414-ec6532e7-7169-4b22-80f3-69be8523e8a2.png)

The Boston Red Sox was the baseball team with the highest beer price per ounce consecutively in 2013, 2014, 2015, 2016, and 2018. This is interesting because they didn't have the most expensive beer price for each year. The Los Angeles Angels had the least expensive beer price per ounce consecutively in 2013, 2014, and 2015 while the Colorado Rockies had the least expensive beer price per ounce in 2016 and 2018.

### Conclusion
My hypothesis was incorrect because baseball teams also had the most expensive beer per ounce or least expensive beer per ounce consecutively. I only thought baseball teams would consecutively have the most expensive beer or least expensive beer. This shows that there will always be a baseball team that will consecutively have the most expensive beer, least expensive beer, most expensive beer per ounce, or least expensive beer per ounce. 
