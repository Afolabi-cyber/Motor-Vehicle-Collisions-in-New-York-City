# Motor Vehicle Collisions in New York City

Welcome to the **Motor Vehicle Collisions in NYC** project. This application is designed as an interactive dashboard, enabling users to explore and analyze motor vehicle collisions in New York City using **Streamlit**. This project provides insights on collision hotspots, collision frequency by time, and street-wise breakdown of incidents involving pedestrians, cyclists, and motorists.

## Project Overview

This project is part of my **12 Days Data Science Project Series**, aimed at exploring and applying data science to real-world scenarios. Day 12 brings together insights and lessons from previous days to examine collision data in NYC, addressing both location-based and time-based analyses.

## Features

- **Collision Heatmap**: Visualize areas in NYC with the highest frequency of motor vehicle collisions.
- **Time-based Analysis**: Track the number of collisions occurring during each hour of the day.
- **Injury Severity Filters**: Customize map views based on the number of injuries reported.
- **Top Dangerous Streets**: Identify streets with the highest incidents involving pedestrians, cyclists, and motorists.
  
This app offers an in-depth view of collision patterns, allowing users to visualize and interact with data in real time. The dashboard structure allows users to explore data dynamically, revealing trends based on location, time, and affected groups.

## Project Objectives

1. **Visualize Collision Hotspots**: Identify high-collision areas on an interactive map using latitude and longitude data.
2. **Analyze Time-based Patterns**: Observe collision frequency across different hours, giving insights into peak times.
3. **Explore Injuries by Affected Group**: Investigate which NYC streets have the highest counts of incidents for each affected group: pedestrians, cyclists, and motorists.
4. **Enhance User Interaction**: Provide users with a customizable, user-friendly dashboard to explore NYC collision data.

## Dataset

The dataset used is the **Motor Vehicle Collisions - Crashes** dataset, publicly available through the NYC Open Data portal. This dataset contains information on collisions, including time, location, injury counts, and factors contributing to the collisions.

- **Columns of Interest**:
  - `CRASH DATE`, `CRASH TIME`: Date and time of each collision
  - `LATITUDE`, `LONGITUDE`: Geographical coordinates for collision locations
  - `NUMBER OF PERSONS INJURED`: Number of injuries in each incident
  - `ON STREET NAME`: Street where the collision occurred
  - Additional columns for specific groups, such as `NUMBER OF PEDESTRIANS INJURED`

## Setup Instructions

To run this application on your local machine:

1. **Clone this Repository**:
   ```bash
   git clone https://github.com/username/motor-vehicle-collisions-nyc.git
