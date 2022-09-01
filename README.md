# bikesharing

[link to dashboard](https://public.tableau.com/views/Mod14Challenge_16619965981730/NYCCitiBike?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Overview of the Analysis

The purpose of this analysis is to explore the feasibility of launching a bike share program in Des Moines, Iowa. In order to do this, data was collected from the bike share company Citi Bike in New York, and then analyzed in order to observe riding trends by time, duration, usertype and gender. Additionally, this project demonstrates proficiency in using the program Tableau to handle large amounts of data to make easily accessible graphics for presenting data analysis.

## Results

There are several insights that can be gained through the analysis of the New York data. 

First, it is apparent that the greatest use case for the bike share program is for transportation to and from work spaces. Looking at the usage vs. ride times graph below it is clear to see that the peak times of usage occur before and after working hours. Additionally, riding will increase as the day goes on between work hours, and then taper off after the end of work hour peak.

![image](https://user-images.githubusercontent.com/103979048/187833427-6d24e868-be39-4a4a-9f24-b5a50a228a33.png)

This insight is further supported by this heat map of usage by hour divided by day shown below. The peaks (darkest points) are before and after work hours as well as on the weekends.

![image](https://user-images.githubusercontent.com/103979048/187833465-f1b6de4a-f778-4f4f-8572-948d81b76107.png)

The tendency transcends gender as demonstrated by this heat map separated by gender shown below. Interestingly, there is a noticeable gap in usage on Wednesdays after work. 

![image](https://user-images.githubusercontent.com/103979048/187833502-d67dc7ac-e71e-4ab0-a43f-7ea7ca7a05b5.png)

Next, the Des Moines program should focus on subscription based riding. Looking at the graph below of usertype usage per day divided by gender, it is evident that the majority of usage comes from subscriber users as opposed to per ride customers. In fact there is more usage from female subscribers than any gender customer.

![image](https://user-images.githubusercontent.com/103979048/187833580-2ffd1409-fe09-4469-94c5-0678bda8dc63.png)

Why is female subscriber usage a significant point? From the pie graph below of users by gender, it is clear to see that the significant amount of bike share usage comes from male users. This is why in each of the previous graphs male usage seemed to dwarf female usage. The Des Moines program should expect a high amount of male usage but also run promotions to increase the female users and capture more of the market.

![image](https://user-images.githubusercontent.com/103979048/187833637-3735a4be-d4c7-47ff-a135-176ea574c2bc.png)

Finally, bike share programs should expect bike usage of less than an hour. According to the graph below, users most commonly rent bikes for 5 minutes. Therefore, Citi Bike share program is more about utility and not as much about recreation. The Des Moines program should focus on supplying bikes near frequent commuting areas instead of further from business centers.

![image](https://user-images.githubusercontent.com/103979048/187833718-20606939-d9ff-4b51-b412-72f444c04ebd.png)

When comparing duration based on gender as on the graph below, the female users proportionally use the bikes longer than male users as evident from the difference in peak usage time.

![image](https://user-images.githubusercontent.com/103979048/187833779-772c3f81-fc72-487f-8420-8edb82678dcb.png)



## Summary

In conclusion, based on the trends of New York’s Citi Bike company the Des Moines program should focus their deployment to support users who need to take a short commute to work. There should be a subscription model and they should expect large usage from a male community. 

In order to understand when usage might be more recreational and thus longer in duration a new heat map should be created that uses the daily/hourly sections and colors them based on duration of use. The expected results would be “hotter” during the weekends and between working hours as users during these times are likely not using the bikes to get to work.

One more visualization that could aid the understanding of bike usage would be a graph of distance traveled for the bikes. In order to do this there would need to be an additional column of data created from the start and stop longitudes and latitudes to find the delta of the position. This visualization would help create a reasonable expectation of how far bikes would need to be brought back when “resetting” bike locations.
