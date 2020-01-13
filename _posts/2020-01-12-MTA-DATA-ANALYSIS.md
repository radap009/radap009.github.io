---
layout: post
title: MTA Data Analysis
---

When I was asked to do exploratory data analysis on the MTA data, my first instinct was to use my expertise in excel and wrap it up in couple of hours. That would have been a short term gain but definitely at long term cost. After couple of days of turmoil with in my Juypter notebook I was able to successfully complete my analysis.

During my previous life as a financial analyst the data I was working was not huge and still the excel would crash after I work on the same excel for a few weeks.  But with Python, the performance remains exactly the same if I am using the same amount of data and perform the same analysis.

Now getting back to my analysis of the MTA data which I worked with Noha and Pang, we made the assumption that the more interactions we can create between street teams and New Yorkers the more email address the street teams will be able to collect. For arriving at this we used the entries as a proxy for number of people arriving at the stations. Secondly, we excluded the weekends as the proportion of tourists would be high and the interactions that the street teams had with tourists could be considered a waste of time (in this context). 

Working through these assumptions we arrived at the top stations with the highest weekday traffic and almost all of them were in Manhattan

![avg_per_day](https://github.com/radap009/radap009.github.io/blob/master/images/avg_per_day.svg)


Digging down even further, we recommend Tuesday through Thursday and the best days to target New Yorkers at stations for getting as many email address as possible.

![avg_weekdays](/images/avg_weekdays.svg)


