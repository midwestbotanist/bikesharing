# bikesharing
[link to dashboard] https://public.tableau.com/app/profile/rachel1064
## Background and Overview:

Bikesharing companies have been popping up in cities across the US. This has been a lucrative business as it helps to alleviate the need for vehicle travel - an issue in cities with large populations due to the amount of congestion the traffic creates on roads/streets, particularly during morning and evening rush hours. Aside from improving traffic conditions by helping to remove the number of cars driving daily, this also can prove to be much cheaper transport for residents as it removes the costs for vehicular upkeep (fuel, carwash, insurance, parking, etc...). 

The purpose of this analysis is to analyze the pros/cons of creating a bikesharing program in Des Moines, IA. 
### When implementing such a program, it is important to know:

* Typical trip duration times
* Total number of trips taken daily every hour for every day of the week, for all riders and then also with the gender comparison
* Total number of trips taken when comparing user type and gender for each day of the week

### The deliverables of this analysis are:

1) Change trip duration to a datetime format
2) Create visualizations for the trip analysis
3) Create a story and report for the final presentation (to be presented to the investors)


## Results:

### 1) The following visualization shows the tyipcal trip duration with number of trips in a breakdown by gender during peak hours. As can be seen here and the following results, male users are the most active users. In fact, the overall usage averages out to follow the way male users take their bike trips. 

![Deliverable3_NYC_FinalPresentation_Story](https://user-images.githubusercontent.com/101941048/207474717-87d08613-a73f-482d-b980-7db227f41179.png)

### 2) Based upon the following visualization, it is interesting to note that male and female non-subscribers (customers) are not heavy users, nor does their amount of usage differ much from each other. However, male subscribers take trips significantly more than female subscribers due. Between this and peak hours of usage, this suggests that male subscribers most often take trips to and from work. This is a trend that also suggests true for female subscribers, but overall they make up a much smaller portion of riders. For both men and women, Wednesday is the lighest day of use overall, while Thursday is the heaviest day of use. This would suggest a look into other events in the city and work practices to see why this occurs. 

![Deliverable3_NYC_FinalPresentation_Story _Weekday_Gender_Breakdown](https://user-images.githubusercontent.com/101941048/207474731-29a68781-a606-45ca-9fcb-de0b576139bc.png)

### 3) As seen below, the peak times in the morning are between 7-10am, while the peak times in the evening are 3-7pm. Both are general commute times. It is important to know peak hours of use as bikes inevitably breakdown and will need to be repaired/serviced at a time they are less likely to be needed. Peak hours of use are important to know because a business must have enough extra bikes at stations to be able to cover all likely users when bikes have been taken away for repairing. I appears Wednesday during morning and afternoon commute happens to be one of the best times to conduct repairs, as well as early hours of Sunday and Monday morning.

![Deliverable3_NYC_FinalPresentation_Peak_Hours](https://user-images.githubusercontent.com/101941048/207474745-01a5f6cf-3faa-4164-a838-be3b94c52b01.png)

### 4) Below is a map depicting the top starting and ending locations. The data tells us that the top starting and ending locations happen to be essentially the same. This is good to know because it is likely the same users commuting to and from those stations leaving the bikes, which also indicates where bikes noted to need repair will likely be. This allows a business to more efficiently develop routes for their workers to check on/service bikes. Additionally, this is very important as the stations with the heaviest usage will need the most bikes - which means keeping the station stocked with enough bikes will keep the users happy and more likely to continue business.

![Deliverable3_NYC_FinalPresentation_Start_End_Locations](https://user-images.githubusercontent.com/101941048/207474782-e1bf54c2-fafa-4e8b-bdc9-d6d0d0131116.png)


## Conclusions:

There are several conclusions that can be drawn from the results, of which several have been stated above. Here the main conclusions will be emphasized and future suggestions will be listed.

### Top Conclusions:
1) Most users are male commuters, so on one hand this is the audience best to targer/cater to...however, this also means there is an opening to find a way to market to and attract female commuters
2) Based upon results, most usage takes place during typical commuting hours for work, though weekends do see some peak usage during the middle of the day. Best times to repair would be Wednesday during non-peak hours and early Saturday/Sunday mornings.
3) Non-subscribers do not utilize the rideshare program much, however subscribers appear to be regularly loyal to the program. This suggests that finding subscribers will be important to the success of the business.

### Future Suggestions:
1) This study was to look over data in New York, however the culture may differ in Des Moines and so sending out surveys as it would be advisable to see how the residents overall are interested in the program - and if any are current users of the existing program and if they believe their are enough bikes/bikes serviced well. A visualization heat could be created to show the level of interest that occurs between gender and ages. 

2) Bikesharing programs are cost-friendly and great solutions for improving congested city traffic. However, investors need to keep in mind that Des Moines, IA already has a bikesharing program with 27 stations and 200 classic/e-bike options: https://desmoines.bcycle.com/. Below is the BCycle station map, further analysis should be conducted to determine whether additional stations and bikes would be of good investment

![desmoines_bcycle_stationmap](https://user-images.githubusercontent.com/101941048/206931346-4b416274-4eaa-4fab-b0e5-3ec4966ed307.png)

Because of this, it would be important to check on usage data to see if there is even space for another bikesharing program to exist in Des Moines. A visualization could be created here to compare usage data on the map against a map showing where survey responders would like to see more stations occur - including an option to compare how many currently use the rideshare program vs those who don't. This is important to know as many may respond out of a desire to use the program, but already live near a station and yet don't currently utilize. 

### Overall:
This program seems to be well loved by subscribers, particularly male subscribers, who commute via bikes to work. However, the competition may be high considering one business already exists. More analysis and surveys are necessary to determine whether a second business of this type could be profitable.


## Sources:
* Python, Pandas, Tableau
* NYC citibike trip data: https://ride.citibikenyc.com/system-data
* NYC code found in the "201908-citibike-tripdata.csv.zip" file on this page: in https://s3.amazonaws.com/tripdata/index.html
