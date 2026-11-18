# Cyclistic Bike Share Analysis

Google Data Analytics Capstone project exploring Cyclistic bike share usage with Excel and Tableau.

## Project Question

**Through looking at the data of casual riders and Cyclistic members, how could we convert people who aren't members into members?**

## Project Materials

- **[Raw data samples](data/samples/raw/)** - samples of the raw data, from Divvy's public trip data for April and October 2025 (used as Cyclistic's data in the capstone).
- **[Cleaned data samples](data/samples/cleaned/)** - samples of the same data after I processed and cleaned it.
- **[Sample data notes](data/samples/README.md)** - notes on how to interpret the data, and the reasoning behind each cleaning step.

- Due to GitHub restrictions, I have limited both the raw data and cleaned data to 20 rows each. This has led to an inaccuracy in mode, mean and maximum inside the sample. I have not changed these measurements to reflect the sample, as they should only be representative of the entire spreadsheet.

## Cleaning and Analysis

- The raw data had 1,017,380 trips (371,341 in April and 646,039 in October), cleaned to 659,336 trips (212,071 casual and 447,265 member).
- The process of cleaning includes but is not limited to: correcting date and time formats, removing ride length outliers (using the interquartile range), keeping only April rows with TA/KA station IDs, filling blank October stations with "Missing", and removing hidden apostrophes from coordinates.
- April makes up about 9% of the cleaned data, so the findings mainly reflect October.
- Cleaned data was validated using filters and formulas (like quartiles and maximums).
- Using the cleaned data, ride length (as well as its mean and max) and the day of the week where rides start and end (as well as their modes) were calculated, along with a column flagging trips that end on a different day.
- PivotTables were created to compare casual riders and members by ride length, day of the week and start station.
- See the [sample data notes](data/samples/README.md) for reasoning behind cleaning steps.

## Conclusion

- Using the analysis, it can be seen that casual riders take slightly longer trips than members (10:40 against 9:38 on average, about 11% longer) and ride more at weekends, making up 44% of weekend rides against 32% overall. Members ride mostly on weekdays. Casual riders also cluster at waterfront areas: Navy Pier is the only top-10 start station where casual riders outnumber members (3,224 against 1,174 rides).
- Using this, casual riders could be converted into members by advertising memberships near waterfront stations and introducing weekend plans. Making it clearer how membership saves money could also help, although this dataset has no pricing data to test it.

## Tableau Dashboard

- **[Published Dashboard](https://public.tableau.com/views/Cyclistic_17942426221390/CyclistDataDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)** - visualisations of the processed data

## Tools

- Excel · Tableau
