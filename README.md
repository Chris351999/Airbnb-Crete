# Airbnb-Crete

## Overview

This project analyzes the impact of Airbnb listings in Crete using publicly available data from [Inside Airbnb](https://insideairbnb.com/crete/). The goal was to explore pricing, availability and the effects of short-term rentals on the local housing market and economy.

## Data Source

The data for this project comes from Inside Airbnb, which provides publicly available information on Airbnb listings worldwide. The dataset for Crete includes information on listing details, host activity, pricing and many more.

Download the latest Crete dataset here: [Inside Airbnb - Get the Data](https://insideairbnb.com/crete/)

## Objectives

1. Understand Airbnb's impact in Crete

* Analyze the number of listings and their distribution across different regions of Crete.

2. Analyze pricing trends

* Determine the average price per night per region.

* Identify factors affecting Airbnb pricing (e.g., seasonality, property type, location).

3. Host behavior analysis

* Identify the proportion of multi-property hosts vs. individual hosts.

4. Availability and occupancy trends

* Assess how many properties are available year-round.

* Understand how Airbnb supply fluctuates over time.

## Installation & Requirements

To replicate this analysis, you will need:

* R

* Required libraries:

  * library(tidyverse)
  * library(ggplot2)
  * library(dplyr)
  * library(readr)
  * library(leaflet)

## Data Exploration

* Data cleaning and preprocessing

* Data wrangling

* Exploratory Data Analysis 

* Visualization of key trends using R libraries like ggplot

## Most Popular Neighbourhoods by Listings

This section ranks neighbourhoods by the number of Airbnb listings, starting with the areas that have the highest concentration of rentals. A bar plot has been added to visually represent the top 10 neighbourhoods by the number of listings.
This section ranks neighbourhoods by the number of Airbnb listings, starting with the areas that have the highest concentration of rentals.

## Neighbourhood Price Analysis

A detailed table presents the price distribution across different neighbourhoods, sorted from the highest to the lowest median price. This analysis provides insights into:

* Median price per neighbourhood

* Mean price per neighbourhood

* Standard deviation per neighbourhood

* Number of listings per neighbourhood

After that, I selected the top 10 most expensive neighbourhoods and created a dot-and-line plot. I plotted the median price in red and the mean price in blue, connecting them with a dashed gray line. 

### Histogram of Airbnb Prices in Crete with Mean and Median Lines

To visualize the distribution of Airbnb listing prices in Crete, a histogram has been created. This plot displays the frequency of different price amounts while also including reference lines for the mean and median prices, providing insights into price distribution trends.

## Daily Pricing Trends

A graph has been generated to display the average price per listing on a daily basis. 

## Availability per Day

To analyze and visualize the availability of Airbnb listings per day, listings were filtered and counted based on availability, grouped by date, and plotted to show trends over time.

## Histogram of Number of Reviews per Listing

To analyze and visualize the distribution of reviews per Airbnb listing in Crete, a histogram has been created. This plot displays the frequency of different review counts while also including reference lines for the mean and median, providing insights into review patterns.

## Room Type Distribution and Pricing Analysis

I analyzed the distribution of different Airbnb room types in Crete to understand how prices vary and how common each room type is. I used a bar plot, violin plot, and frequency analysis to explore these insights.

## Interactive Map of Airbnb Listings in Crete

I aimed to analyze and visualize the geographic distribution of Airbnb listings in Crete using an interactive map. This map allows users to explore locations dynamically, view listing details, and see how room types are distributed geographically.

## Listings per Host

In this analysis, I examined the number of listings per host to understand hosting behavior and identify whether a majority of listings are managed by individual hosts or multi-property operators.

## Future Work

* Machine learning predictions for price optimization

* Comparative study with other Greek islands

## Contact Information
* Name: Christos Fakontis
* Email: fakontis.christos@gmail.com
