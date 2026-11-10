# Cyclistic Bike Share Analysis

Google Data Analytics Capstone project exploring Cyclistic Bike Share usage with Excel and Tableau.

## Project question

**Through looking at the data of casual riders and cyclistic members, how could we convert people who aren't members into members?**

## Project materials

- **[Raw data samples](data/samples/raw/)** — samples of the raw data taken from Google's Cyclistic database.
- **[Cleaned data samples](data/samples/cleaned/)** — samples of the same raw data processed and cleaned by me.
- **[Sample-data notes](data/samples/README.md)** — notes on how to interpret the said data.

- Due to GitHub restrictions, I have limited both the raw data and cleaned data to 20 rows each. This has lead to an inaccuracy in mode, mean, and maximum inside the sample. Where possible, I have not changed said measurements to reflect the sample, as they should only be representative of the entire spreadsheet.

## Cleaning and Analysis

- The process of cleaning includes but is not limited to; date format correcting, removing inaccurate data and outliers (calculated using interquartile range for quantitative data and removing illegitimate qualitative data), filling in empty spaces with "Missing" where data doesn't fulfill the requirement of an outlier and keeping longitude and latitude to 4 d.p.
- Cleaned data was validated using filters and formulas (like quartiles and maximums).
- Using the cleaned data, ride length (as well as its mean and max) and the day of the week where rides start and end (as well as their modes) were calculated. A column where the number of trips change day has been included.
- PivotTables have been created.
- See the [sample-data notes](data/samples/README.md) for reasoning behind cleaning steps.

## Tableau Dashboard

- **[Published Dashboard](https://public.tableau.com/views/Cyclistic_17942426221390/CyclistDataDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)** - Visualisations of processed data

## Tools

- Excel · Tableau
