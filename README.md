# Citi Bike Startup Exploratory Data Analysis in Tableau

The annotated Tableau Public story can be found at: https://public.tableau.com/app/profile/sue.mottet/viz/NYCCitiBike_16410710320630/NYCCitiBikeStory?publish=yes

## NYC Citi Bike Exploratory Data Analysis Overview

This project is to perform exploratory data analysis on one month of NYC Citi Bike data to determine how best to be successful with a similar program in Des Moines.

The exploratory data analysis includes: 

* inspecting the data
* converting dates formated as integers to datetimes (hours, minutes, and seconds).
* exporting converted data to a .csv file
* performing calculations
* creating data visualization in Tableau
* building dashboards and a story to present the data visualizations

### Objective 1: Download, inspect and prepare the data for analysis

1. Using Python and Pandas functions, "tripduration" data is converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). 
2. After conversion of the "tripduration" data to a datetime dataytpe, the DataFrame is exported as a CSV file to use for trip analysis.
3. The converted dates show with the datetime format in Tableau as shown here:

![converted date image](/Resources/trip_duration_minutes_conversion.png)

### Objective 2: Create data visualizations to present key findings to be utilized by Des Moines for determining and improving startup success

Using Tableau, visualizations are created to present:

- An overview of the Citi Bike information in NYC program profiling
- How long bikes are checked out for all riders, by gender, and by age
- How many trips are taken by the hour for each day of the week, for all riders and genders
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender
- Maps identifying the best start and end bikes station locations in NYC to help the Des Moines better understand type of station locations used most frequently
- Other useful program details

### Objective 3: Using Tableau and this README to tell the NYC Citi Bike story
Provisioning the exploratory data analysis in a digestible format shares information around key outcomes relevant for determining and possibly improving the chances of the success of a similar Des Moines program startup.

This objective is accomplished with:

 - a story in Tableau Public
 - written analysis that describes the key outcomes of the NYC Citi Bike analysis (README)

### Resources: 

- Software: Tableau Public, Python 3.6.1, Jupyter Notebook, Pandas

## Exploratory Data Analysis Results for Citi Bike

Shown below are a sampling of the data visualizations for this exploratory data analysis. 

The annotated story is available on Tableau Public at:
https://public.tableau.com/app/profile/sue.mottet/viz/NYCCitiBike_16410710320630/NYCCitiBikeStory?publish=yes

The Tableau Public annotated story for this exploratory data analysis includes data visualizations for:

### 1. NYC Citi Bike overview information

This dashboard highlights some of the most relevant information around the NYC Citi Bike program that should help the Des Moines program startup.

![bike overview image](/Resources/overview.png)

### 2. Peak bike usage information - usage by hours of the day

This data visualization shows all the usage information by hours of the day and can be found in the Tableau Public story. It provides the full hour by hour usage detail.

### 3. Best performing bike station location information

This data visualization highlights the relationship between places in NYC and bike station usage and should help the Des Moines program identify where to place bike station and how many bikes will be needed.

![bike station image](/Resources/best_start_end_locations.png)

### 4. Bike usage by weekday

This data visualization highlights the heaviest usage times by day of week and hour of day. It should help the Des Moines program plan for the number of bikes and bike placement.

![day weekday image](/Resources/trips_by_weekday_per_hour.png)

### 5. Trip duration by user type

This data visualization highlights the amount of time the riders by gender use the bikes by the type of user and can be used to help the Des Moines program plan for distance between bike stations and bike number at bike stations location around different types of city locations.

![checkout times user image](/Resources/checkout_times_by_usertype.png)

### 6. Trip duration by gender

This data visualization highlights the amount of time the riders by gender use the bikes by the type of user and can be used to help the Des Moines program plan for distance between bike stations and bike number at bike stations location around different types of city locations.

![checkout times user image](/Resources/checkout_times_by_gender.png)

### 7. Hourly bike usage by gender and time of day

This data visualization provides information on when bikes are used throughout the week and during which times of day and can be helpful in planning bike station patterns.

![gender time of day image](/Resources/trips_by_gender_weekday_per_hour.png)

### 8. Usage by gender by weekday

This data visualization provides information on gender breakouts by the day of the week and could be helpful in marketing to each or couples for increasing bike usages and expanding usage.

![gender weekday image](/Resources/user_trips_by_gender_by_weekday.png)

### 9. Average trip duration by birth year (age)

This data visualization provides information on how long bikes are ridden by birth year of the rider (age) and can be found in the Tableau Public story. It should be helpful for the Des Moines program in combination with Des Moines population age information and their city visitors age profiles.

### 10. Trip duration by users

This data visualization provides information on trip duration by user. It can be used to understand how long the bikes are typically checked out for.

![checkout times user image](/Resources/checkout_times_for_users.png)

### 11. Bike utilization by bike 

This data visualization provides information on bike utilization by bike and could be used to help rotate and extend times between bike repairs for the bike program. It can be found in the Tableau Public story.

### 12. Bike repair planning information

This data visualization provides information on how long bikes have been ridden for bike repair planning and can be found in the Tableau Public story.

## NYC Citi Bike Exploratory Data Analysis Summary:

1. Subscriptions are an important part of the NYC Citi Bike program. Customer usage though less consistent is not insignificant and should be factored in for success of the program in Des Moines.
2. Commuting patterns around key areas of commerce in Des Moines should be used to determine bike station locations, the distance between them, and the number of bikes to place at each station.
3. Bike friendly sight-seeing and tourist sites should also be targeted for bike station locations and the site related usage and traffic patterns analyzed to help determine the number of bikes to place at nearby bike stations.
4. Setting up this same dashboard for the Des Moines program and keeping it updated would allow the program to learn more about their bike usage and adapt the program for better continued success.

## References:
* Best practices for effective dashboards: https://help.tableau.com/current/pro/desktop/en-us/dashboards_best_practices.htm
* Tableau website: https://public.tableau.com/en-us/gallery/?tab=viz-of-the-day&type=viz-of-the-day
* tips to make your dashboard more performant: https://www.tableau.com/about/blog/2016/1/5-tips-make-your-dashboards-more-performant-48574
* pandas.DataFrame.to_csv: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html
* Python pandas convert seconds to time (hh:mm): https://stackoverflow.com/questions/44118395/python-pandas-convert-seconds-to-time-hhmm
* Convert Integers to Datetime in Pandas: https://pythonguides.com/convert-integers-to-datetime-in-pandas/
