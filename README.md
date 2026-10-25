# Airbnb_CleanDatasheet
A small practice project where I explore Airbnb listing data using Python, pandas, and charts.

About the data
Source: Kaggle 
About 280,000 Airbnb listings
33 columns, including:
Host info: host since, response rate, superhost, total listings
Location: neighbourhood, city, latitude, longitude
Property: property type, room type, bedrooms, amenities
Price and stay rules: price, minimum nights, maximum nights
Reviews: rating, cleanliness, location, value, and more

What I did
Cleaned the data first. I fixed the dataset before starting the analysis.
Checked the basics. I looked at column types, missing values, and simple stats with df.describe().
Looked at room types.
Made a chart of how many listings are in each room type.
Made a boxplot to compare prices across room types (only prices under 500, so a few very expensive listings do not ruin the chart).
Fixed a plot problem. I got a seaborn warning because two plots were drawn on the same axes. I fixed it by giving each plot its own figure with plt.figure() and plt.show().

Questions I want to answer
What does the price distribution look like?
Which cities are the most expensive?
Do superhosts get better reviews or charge more?
Does the number of guests (accommodates) change the price?
Which review scores are connected to each other?
When did most hosts join Airbnb?

Tools used
Python
pandas
matplotlib
seaborn
Jupyter Notebook

What I learned
How to explore a big dataset with pandas
How to make charts with matplotlib and seaborn
Why each chart should have its own figure
Why outliers matter when looking at price
