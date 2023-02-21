# Bike Sharing Data Visualisations
## Overview of the Statistical Analyisis 
These visualisations display the usage of a bike sharing service to highlight the investment opportunities presented by this business proposal. The visualisation can be accessed [here](https://public.tableau.com/app/profile/theodore.ofner/viz/challengebook/BreakdownofUsageData?publish=yes)

## Results
![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/piess.png)
Our first visualization is a breakdown of users by gender. In orange we have the Male users who we see are by far the largest share, roughly 70% of the user base. The remaining ~30% is comprised of women and unreported users.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/ctfuss.png)
Our second visualisation shows the duration of trips. As we can see, the majority of trips are short distance, between 10 and 20 minutes, with a rapid falloff after 30. 

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/ctfugss.png)
Breaking the trip duration down by gender, we see that the duration trend is consistent across genders, roughly proportional to the usage rates.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/hourlyss.png)
Looking at our hourly usage we can see an expected trend, one peak in the morning, one peak in the evening, with ridership over 80k for most of the day.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/weekdayss.png)
Expanding this out by weekday, we can see that this morning/evening spike is present on workdays, but on the weekends, the pattern changes.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/weekdaygss.png)
Factoring in gender, it is clear that the overall pattern is similar across genders.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/unknown.png)
However focusing in on the unknown category, we can see an unusual clustering of usage times on Saturday afternoon, with little during the week. This is most likely an anomaly due to small subsample proportion.

![](https://raw.githubusercontent.com/SecretDoves3000/bikesharing/main/images/typess.png)
And finally, a chart of usage broken down by day, gender and customer type. We can see the bulk of the user base are male subscribers, and are subscribers overall. 

## Summary
Our analysis shows that there is a strong market for short distance bike sharing amongst men. This mostly consists of trips in the morning and evening on weekdays, regardless of gender. We reasonbly conclude the primary use case is the weekday work commute, and as such, investments should focus on building the product with that primary usage in mind. With this knowledge, we should look at further analysis of repeated usage to see what kind of trips generate new subscriptions and break that down by gender as a way to investigate the gender desparity in usage.
