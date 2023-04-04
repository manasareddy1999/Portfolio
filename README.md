
# Portfolio
#INTRODUCTION OF PROJECT

 This is data set which contains information is City hotel and Resort hotel have seen high cancellation rates.Each hotel is now dealing with a number of issues as a result, including fewer revenues and less thn ideal hotel room use.
 
 Consequently ,lowering cancellation raters in both hotels primary goal in order to increase thier efficieny in generating revenue ,and for usto offer through business advice to address this problem .
 
 The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue genration are the main topics of this report.
 
## RESEARCH QUESTION
 
 1.What are the variables that affect hotels reservation cancellations ?
 
 2.how can we mke hotel reservations cancellations better?
 
 3.how will hotels be assisted in making pricing and promotional decisions ?
 
## Code and Resources Used
 
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import warnings
warnings.filterwarnings(‘ignore’)

import seaborn as sns

pd.read_csv(‘/content/drive/MyDrive/hotel_bookings 2.csv’)

## Data Cleaning

After scraping the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

converting ‘reservation_status_date’ to date time format

Removing the ‘company’,‘agent’ removing both columns because these contain more null values by removing these columns the data set does not affect

droping all null values

df=df[df[‘adr’]<5000] because it only one value above 5000

## Data Analysis and visualizations

The graph is plot to see percentage of canceled and not canceled
![graph](https://user-images.githubusercontent.com/124489708/229761228-08839513-dd91-46a7-868c-a9b9e55e6ea0.png)


The accompanying bar graph shows the percentage of reservations that are canceled and those that are not. It is obvious that are still a significant number of reservations that have not been cancelled. these are still 37% of clients who canceled thier reservations which has a significant impact on the hotel’s earnings.

![photo](https://user-images.githubusercontent.com/124489708/229763069-414cd337-a9c4-4669-920f-6f889eaeaeee.jpg)

In comparison to resort hotel’s,city hotels have more bookings. It’s possible that resort hotels are more expensive than those cities.

![graph3](https://user-images.githubusercontent.com/124489708/229763192-b7f18137-9a78-440c-8b82-a86757c89f97.png)


The line graph above shows that,on certain days, the average daily rate for a city hotel is less than of a resort hotel. and on other days it is even less. it goes without saying that weekends and holidays may see a rise in hotel rates.

![graph4](https://user-images.githubusercontent.com/124489708/229763325-340c6185-021e-4ba2-88b8-f83734d8a3a3.png)


we have developed the grouped bar graph to analyze the months with the highest and lowest reservations levels according to reservation status.As can be seen, both the number of confirmed reservations and the number of canceled reservation are largest in the month of august where as january is month with the most canceled reservation.

![graph5](https://user-images.githubusercontent.com/124489708/229763434-20087eca-bbce-4917-a1c2-0d19ab70c794.png)

this bar graph demonstrates that cancellations are most common when prices are greatest and are least common when they are lowest. therefore, the cost of the accommodation is only responsible for cancellation.

Now,let’s see which country has the highest reservation canceled.the top country is Portugal with the highest number of cancellations.

![graph6](https://user-images.githubusercontent.com/124489708/229763912-501e77d4-8534-4f8d-b8e7-3848a8cab504.png)


Lets check the area from where guests are visiting the hotels and making reservatios.Is it coming from Direct or Groups, Online or Offline Travel Agents? Around 46% of the clients from online travel agencies ,whereas 27% come from groups .Only 4% of clients book hotels directly by visiting them and making reservations

As seen in graph ,reservations are canceled when the average daily rate on higher than when it is not canceled. it clearly proves all the above analysis, that the higher prices leads to higher cancellation.

Suggestions
Cancellation rates rise as the price does. In order to prevent cancellations of reservations, hotels could work on their pricing strategies and try to lower the rates for specific hotels based on locations .They can also provide some discounts to consumers.

As the ratio of the cancellation and not cancellation of the resort hotel is higher in resort hotel than the city hotels .So the hotels should provide a reasonable discount on the room prices on weekends or on holidays

In the month of january ,Hotels can start campaigns or marketing with reasonable amount to increase their revenue as the cancellation is the highest in this month.

They can also increase the quality of their hotels and their serives mainly in Portugal to reduce the cancellation rate.
 

