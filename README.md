# Exploring Airbnb Market Trends

#### Table of Contents
- [Overview](#overview)
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Data Merging](#data-merging)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)
  
#### Overview
This project analyzes the Airbnb listings data in New York from three datasets to extract insights.

#### Introduction
The objective of this project is to perform data analysis on Airbnb listings to extract insights related to review dates, room types and pricing.

#### Data Sources
This project contains the following 3 datasets
- airbnb_price.csv
- airbnb_room_type.xslx
- airbnb_last_review.tsv
  
#### Data Merging
The three datasets are merged using the common field "listing_id" to create a single DataFrame.

#### Analysis
The analysis involves:
1) Determining the earliest and most recent review dates.
2) Finding the number of listings that are private rooms.
3) Calculating the average price of listings.
   
#### Results
The results of the analysis are stored in a DataFrame which includes First Reviewed Date, Last Reviewed Date, Number of Private Rooms, Average Price.

#### Conclusion
This project provides useful information about review trends, room types and pricing for Airbnb listings.
