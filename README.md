CitiBike-Analysis

For this challenge, i used data from the New York Citi Bike Data to create phenomenas, 
visualize that explains the data and generate a dashboard in Tableau.

https://public.tableau.com/app/profile/jajuan.graham/viz/Top10Start/Top10Start?publish=yes

I used data from February and July of 2024 to show the difference in data from two different timeframes.
I used Python to clean and combine the data. I also cleaned and updated word phases and timelines to showcase appropriate dates and times. I removed any null or data that presented a zero value.

Jupyter Notebook with data 
Combined data CSV was used to create the Tableau visuals

Analysis
-----------------------------------------------------------------------------
## Citi Bike Utilization Analysis

Utilization by Bike Type

Electric bikes show higher usage, with 333 distinct ride IDs compared to 167 for classic bikes. This reflects the growing demand for faster, less physically demanding transportation options, particularly in dense, high-traffic areas.

**Key Observations:**

* Electric bikes have roughly twice the ride count of classic bikes.
* Likely reflects commuter preferences for efficiency and convenience.

Trip Duration by User Type

Casual users tend to have a broader range of trip durations, while members show more consistent, shorter rides, suggesting more regular, purpose-driven trips.

**Key Observations:**

* Casual riders take a wider variety of trip lengths, often for leisure.
* Members stick to shorter, more consistent trips, likely for commuting.

Station Trends and Usage Patterns

#### Top 10 End Stations

Bar charts highlight the most frequent end locations. W 24 St & 7 Ave and W 44 St & 11 Ave are the top destinations, with some trips ending at unknown stations, indicating data gaps.

**Key Observations:**

* High trip volumes at key intersections in Manhattan.
* Some data gaps with "unknown" station entries.

#### Top 10 Start Stations

Stations like W 31 St & 7 Ave and E 33 St & 1 Ave are the most common starting points, each with 5 distinct ride IDs, reflecting their popularity in central Manhattan.

**Key Observations:**

* Popular start points align with major commercial and residential areas.
* Central Park West and other high-foot-traffic areas also rank among the top start locations.

#### Monthly Popularity Trends for Top 10 Starting Stations

This bar chart shows the monthly variation in station popularity, with E 33 St & 1 Ave and W 31 St & 7 Ave consistently ranking high.

**Key Observations:**

* Some stations show stable monthly trends, while others see more seasonal variation.

#### Heat Map of Top 10 Starting Stations

The heat map reveals dense activity in central Manhattan, particularly around Midtown and the Financial District.

**Key Observations:**

* High density in business and tourist areas.
* Likely reflects peak commuter traffic and tourist hotspots.

#### Trip Length and Start Location

Stations with the highest trip lengths include W 31 St & 7 Ave and E 33 St & 1 Ave, indicating these may be popular for longer, point-to-point trips.

**Key Observations:**

* Longer trips may indicate either commuter routes or extended tourist rides.

### Conclusion

Electric bikes dominate usage, member trips are more consistent, and the busiest stations are clustered in Manhattan. Addressing data gaps (e.g., "unknown" stations) and expanding e-bike availability could improve system efficiency and user experience.


More Visuals
------------------------------------------------------------------------------
https://public.tableau.com/app/profile/jajuan.graham/viz/TripDurationbyUserType_17467210038510/BikeType?publish=yes

https://public.tableau.com/app/profile/jajuan.graham/viz/AverageTripDuration_17467208588110/AverageripDuration?publish=yes

https://public.tableau.com/app/profile/jajuan.graham/viz/Top10EndStation_17467209472580/Top10End?publish=yes

<img width="1261" alt="Screenshot 2025-05-08 at 8 46 04 AM" src="https://github.com/user-attachments/assets/04945cd8-f9dd-483e-8042-981b3a891c3f" />

<img width="1255" alt="Screenshot 2025-05-08 at 8 46 11 AM" src="https://github.com/user-attachments/assets/0366fe72-a16b-436f-ba1f-40b3313d546b" />

<img width="1255" alt="Screenshot 2025-05-08 at 8 46 11 AM" src="https://github.com/user-attachments/assets/26e1e579-5a36-4e7b-8628-f09572de367b" />

<img width="1267" alt="Screenshot 2025-05-08 at 8 46 19 AM" src="https://github.com/user-attachments/assets/5a1dbefe-a676-4ede-a5ba-ad9fec7ca83f" />

<img width="1259" alt="Screenshot 2025-05-08 at 8 46 32 AM" src="https://github.com/user-attachments/assets/ebb60ed5-3ec1-46d4-9127-11c090777d64" />

<img width="1260" alt="Screenshot 2025-05-08 at 8 46 51 AM" src="https://github.com/user-attachments/assets/5865a615-ba1b-4644-ab79-1a4752ae7055" />

<img width="1262" alt="Screenshot 2025-05-08 at 8 47 09 AM" src="https://github.com/user-attachments/assets/1c2e00ed-6815-4d77-a123-a5b094e961cd" />

