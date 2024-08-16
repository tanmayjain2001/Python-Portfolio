# Python-Portfolio
Welcome to my Python Portfolio repository! This repository contains a collection of Python projects that demonstrate my skills and expertise in working with databases. Each project is accompanied by Python code, documentation, and sometimes additional resources.


# Table of Contents -
(1.) Hotel Booking Data Analysis

This project involves a thorough analysis of hotel booking data to uncover insights, identify patterns, and clean and transform the data for better usability. The data comprises multiple datasets, including booking details, hotel information, room categories, and aggregated bookings.

Table of Contents

* Project Overview

* Datasets

* Data Exploration

* Data Cleaning

* Data Transformation

* Insights

* Libraries Used

* How to Run

# Project Overview

The objective of this project is to analyze hotel booking data, clean the data by removing inconsistencies and outliers, and transform the data to generate meaningful insights. Visualizations are created to better understand the distribution and trends within the data.


# Datasets

fact_bookings.csv: Contains detailed booking information.

dim_date.csv: Contains date-related information.

dim_hotels.csv: Contains details about hotels.

dim_rooms.csv: Contains information about room categories.

fact_aggregated_bookings.csv: Contains aggregated booking information.

# Data Exploration

Fact Bookings

Total records: 134,590

Unique room categories: RT1, RT2, RT3, RT4

Booking platforms: direct online, others, logtrip, tripster, makeyourtrip, journey, direct offline

Visualizations

Booking platforms distribution: Bar chart

Summary statistics: Descriptive statistics for numerical columns

Dim Hotels

Hotel categories and cities distribution: Bar charts

Category-specific city distribution: Bar charts for Luxury and Business categories

Fact Aggregated Bookings

Successful bookings per property ID

Days with bookings greater than capacity

Properties with the highest capacity

# Data Cleaning

Fact Bookings
Removed bookings with zero or negative guests
Handled outliers in revenue generated
Addressed missing values in ratings_given

Fact Aggregated Bookings
Filled missing values in capacity with the median value
Filtered out records where successful bookings exceed capacity

# Data Transformation

Occupancy Percentage

Added a new column occ_pct to fact_aggregated_bookings to represent the occupancy percentage calculated as successful_bookings / capacity

# Insights

The dataset has multiple platforms used for bookings, with direct online and others being the most common.

Certain days had bookings exceeding the capacity, indicating possible data entry errors.

Luxury category rooms (RT4) had higher revenue realization, justifying their premium pricing.

# Libraries Used
pandas
numpy
matplotlib
seaborn
