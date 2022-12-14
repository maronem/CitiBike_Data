# CitiBike Analysis

Here is a link to all data figures for this analysis:
[Citi Bike Tableau Data](https://public.tableau.com/app/profile/michael.marone/viz/CitiBike_Challenge_16647958945100/Story1?publish=yes)

# Analysis Summary

The purpose of this analysis was to understand Citi Bike user demographics and tendendies using Tableau. We sought to assess the length of time that bikes are checked out for total riders and genders, the number of trips for all riders and genders per hour of the number of bike trips for each day of the week, and the number of bike trips for each type of user and gender for each day of the week.

# Results

Below are Tableau generated results from the Citi Bike User dataset:

#### Fig 1. Most starting locations for Citi Bike riders are in lower New York City (NYC).

Ride count is signified by circle size and cirlce darkness, showing the largest count and density of ride starting locations are in the lower third of NYC.

![top_start_loc](https://user-images.githubusercontent.com/108199140/194126176-7e6fe2d0-cf4b-49ec-b4dc-8ec156374ed7.PNG)

#### Fig 2. Most ending locations for Citi Bike riders are also in lower NYC.

Ride count is again signified by circle size and cirlce darkness, showing the largest count and density of ride ending locations are in the lower third of NYC, but 
the ending locations can vary as the circle size and darknesses are not always matching.

![end_loc](https://user-images.githubusercontent.com/108199140/194183185-dce4c087-c2d9-4821-9489-2f6dae633519.PNG)

#### Fig 3. A majority of Citi Bike rides last 5 minutes.

Citi Bike ride counts have a steady increase from 1-5 minutes, with a peak at 5 min (146,752 rides, and a steady decline out to 60 min.

![trip_duration](https://user-images.githubusercontent.com/108199140/194128093-48abb345-90f8-4ed5-a49a-99b348efd3cc.PNG)

#### Fig 4. The most popular times to end Citi Bike rides vary depending on time of the week.

This generated heat plot shows denisty of rides stopped during 1 hour bins. High counts are indicated by dark red, while low counts are indicated by yellow. These data show a majority of riders end their rides between 7-9am and 5-7pm during the week, while rides end continuosly throughout the day on the weekends.

![stop_times](https://user-images.githubusercontent.com/108199140/194130331-8786ead3-4340-435b-aa54-cd536b30b26d.PNG)

#### Fig 5. The most popular times to end Citi Bike rides vary depending on time of the week.

When looking at the data parsed by gender (Male, Female, or Unknown), the same outcome of a majority of rides spanning 5 minutes holds for both males and females, while male users overall have a higher ride count. Interestingly, those who did not specify their gender have a more spread out ride time spanning from approximately 5-30 mins.

![trip_duration_gender](https://user-images.githubusercontent.com/108199140/194132056-4914e82d-493e-421e-a88f-1b9aa423707a.PNG)

#### Fig 6. Citi Bike ride counts are highest on Monday-Tuesday and Thursday-Friday, regardless of gender.

The below heat map shows ride count by gender and day of the week. Overall, the heat map is stronger in the male column as there are more Male riders compared to females. Regardless of this, the heat map shading is similar between both Males and Females with the highest round count days as Monday-Tuesday, Thursday-Friday, with the highest overall ride counts being on Thursday.

![trip_volume_gender](https://user-images.githubusercontent.com/108199140/194147206-ed3c548c-fdcf-4df5-aee6-9617ae269cb9.PNG)

#### Fig 7. Citi Bike ride stop times do not differ between genders.

When parsing the Citi Bike ride stop time heatmap to the following when stop times are parsed by Gender, the heat maps show the same patterns with a majority of riders ending their rides between 7-9am and 5-7pm during the week. Additionally, the same pattern is shown on the weekends with rides ending continuously throughout the day. The weaker heatmap intensity for females matches that there are less female users, but does not change any data pattern compared to male users.

![stop_times_gender](https://user-images.githubusercontent.com/108199140/194147943-e7755591-f742-4a7e-9b85-f8bfc70046ce.PNG)

# Summary

These data show that Citi Bike users start and end their rides mostly in the lower third of NYC with some of the return locations being as active as the starting locations, while some vary in popularity. Users ride times vary from 1-60 min but a majority of user rides are 5 min in duration, and this holds regardless of gender. Thse quick rides could be due to users riding to work for short distances as ride counts are highest both in the morning (7am-9am) and evening (5pm-7pm) around the time people go to work and head home during the week. While there are overall more male Citi Bike users, this trend holds for female Citi Bike users as well. Lastly, while investigating ride volume per day by gender, both male and female Citi Bike users ride mostly during the week with the highest ride counts during Mon/Tues and Thurs/Fri. Overall these data show that both male and female Citi Bike users mostly use Citi Bikes for short rides in the morning and evening during the week during times associated with morning and evening rush hour. 
 
One additional analysis that could be performed would be to investigate ride start times per hour binned by birth year. To investigate the hypothesis that short ride times and riding hours are due to work hours, looking at a heat map of Citi Bike users in a working age range (ie. 20-60) to see if the heat map pattern matches the one generated for all users. A second future analysis could be to determine if males and females visit similar or different locations. To do this you can map ending location latitude and longitude and color these points by Gender to determine which Gender stops at each station more often.
  
  
