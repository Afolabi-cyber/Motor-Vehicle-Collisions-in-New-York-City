# NYC Motor Vehicle Collisions Analysis Dashboard

This project is part of my "12 Days Data Science Project" series, rounding off the series with an interactive data dashboard that provides insights into **motor vehicle collisions** in New York City. The project uses the Motor Vehicle Collisions - Crashes dataset to analyze the factors contributing to these incidents, helping to identify areas with high injury rates and dangerous locations for pedestrians, cyclists, and motorists.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

## Overview
This dashboard visualizes motor vehicle collision data across NYC, enabling users to:
- View geographical distributions of collisions.
- Identify times and locations with the highest numbers of injuries.
- Analyze dangerous streets for different affected groups.

The dashboard was built using **Streamlit** for interactive visualizations, **pandas** for data manipulation, and **plotly** and **pydeck** for mapping and charts.

## Features
- **Interactive Collision Map**: Use a slider to filter collisions by injury count and hour.
- **Hourly Collision Data**: Filter data by hour to view collisions within a specific time frame.
- **Top 5 Dangerous Streets**: Identify high-risk streets based on the type of user (Pedestrians, Cyclists, Motorists).
- **Minute-by-Minute Breakdown**: Visualize the frequency of collisions by minute within the chosen hour.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/motor-vehicle-collisions-dashboard.git
