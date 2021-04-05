# bikesharing

## Project Overview

Analyzing Citi Bike data for August 2019 to be used in the business propopsal for the potential bike sharing program in Des Moines, Iowa. This analysis will be providing details on the following:

- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
- Geographical insight on the top starting & top ending locations.

The Tableau story can be viewed [here](https://public.tableau.com/profile/josh.bissessar#!/vizhome/NYCCitibike_16171447740660/Aug2019TripAnalysis)

## Resources

Data Source: [August 2019 Citi Bike Trip Histories](https://s3.amazonaws.com/tripdata/index.html)
Software: Tableau Public 2021.1.0, Jupyter Notebook 6.1.4

## Results

#### 1. Checkout Times for Users

<p align="left">
  <img src="resources/checkout_times_for_users.PNG" width="800"/>
</p>

- Majority of users checkout bikes for a duration under 20 minutes.

#### 2. Checkout Times by Gender

<p align="left">
  <img src="resources/checkout_times_by_gender.PNG" width="800"/>
</p>

- Majority of the users that checkout bikes for under 20 minutes are male.

#### 3. Trips By Weekday per Hour

<p align="left">
  <img src="resources/trips_by_weekday_per_hour.PNG" width="800"/>
</p>

- Majority of bike trips are taken between 7:00 a.m. - 9:00 a.m. and 4:00 p.m. - 6:00 p.m.

#### 4. Trips by Gender by Weekday per Hour

<p align="left">
  <img src="resources/trips_by_gender_weekday_per_hour.PNG" width="800"/>
</p>

- Majority of Citi Bike users during weekdays between the hours of 7:00 a.m. - 9:00 a.m. and 4:00 p.m. - 6:00 p.m. are male.

#### 5. User Trips by Gender by Weekday

<p align="left">
  <img src="resources/user_trips_by_gender_weekday.PNG" width="800"/>
</p>

- Majority of subscribers are male, with a larger number of trips occuring on Monday, Tuesday, Thurday and Friday.

#### 6. Top Starting Locations
<p align="left">
  <img src="resources/top_starting_locations.PNG" width="800"/>
</p>

#### 7. Top Ending Locations
<p align="left">
  <img src="resources/top_ending_locations.PNG" width="800"/>
</p>

- There is a larger number trips starting and ending in the Lower Manhattan area.

## Summary

Recommendations for other visualizations for potential investors:

1. Trips by Age by Gender

<p align="left">
  <img src="resources/trips_by_age_by_gender.PNG" width="800"/>
</p>

2. Trips by Usertype by Gender

<p align="left">
  <img src="resources/trips_by_usertype_by_gender.PNG" width="800"/>
</p>
