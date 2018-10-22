# Kaggle-Airplane-crash-history-project

I used Airplane Crash History Dataset from Kaggle availbale here: https://www.kaggle.com/saurograndi/airplane-crashes-since-1908
to get some insights about historical airplane crash incidents.

Main idea: Find interesting insights by focusing on plane crash data from WWII

1) Fatalities faced by major players in WWII

2) Distribution of times during the day when these crashes happened

3) Finding deadliest decade in airplane crash history

Discussion of analysis and results:

Fatalities faced by major players in WWII:

The data included the location of each crash incident but in order to figure out the fatalities for each country I had to combine the information about country of plane manufacturer with the number of deaths which occured aboard (home country fatalities) and on the ground (enemy country fatalities).

During the war planes could have crashed in the home country due to problems with internal working of the plane or while being in another country's air space. I needed to take into account the number of deaths which occured on board and on ground.
After looking into the data I only need to account for fatalities aboard the plane as they were the key figure in total death computation. An observation in this scenario: during the war it was highly likely that only fatalities on board could be properly reported beacuse if a plane crashed in home territory the pilots must have tried to make sure that it was not flying over populated regions; if a plane crashed outside of home territory it was very unlikely to get the count for on the ground deaths. 

Once I added information about the country of origin of each plane, I only needed to count the fatalities on board to get a total count for fatalities faced by that country. 

Distribution of times during the day when these crashes happened:

I was interested in figuring out the part of the day in which the likelihood of plane crashes was the highest as I assumed it would point out to the part of the day in which most air attacks happened. 

Using data for time of crashes which was available, I found out that there was no coorelation between the time of crash with the time of day. 

Finding deadliest decade in airplane crash history:

By grouping the yearly data, I found out years 1970-1979 have been the deadliest in plane crash history. However, despite technological advancements the death toll hasn't dropped significantly since then, resulting in 20000 lives lost in plane crashes during years 2000-2009.
