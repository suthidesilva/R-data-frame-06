# The Roller Coaster Database

## Overview

This analysis utilizes data from rcdb.com, The Roller Coaster Database, collected in 2015. The dataset includes various attributes of roller coasters, such as their names, the theme parks they belong to, track types, speed, height, drop size, length, duration, and whether they include inversions.

## Data Loading

The roller coaster data is loaded from the file `coasters-2015.csv`. The first 10 rows of the dataset are displayed to provide an initial overview.

## Data Cleaning

It was observed that some columns contained ".", which could be considered as errors. To address this, the "." values were replaced with zero to ensure data integrity and prevent data loss.

## Questions Explored

### 1. Visualizing Roller Coaster Attributes

Four variables were selected for visualization, including at least one categorical variable. Two scatter plots were created using different combinations of variables:

a. **Scatter Plot 1**: Length vs. Height with different tracks and inversions represented by color and point size, respectively.
b. **Scatter Plot 2**: Speed vs. Height with different inversions and tracks represented by color and point size, respectively.

The selection of variables for the axes was based on identifying two quantitative variables that could potentially exhibit interesting relationships. The inclusion of two categorical variables allowed for additional insights to be derived from the scatter plots.

### 2. Exploring Correlation in Roller Coaster Attributes

The potential correlation between roller coaster attributes, specifically height and length, as well as height and speed, was investigated. Scatter plots with best-fit lines were created to visualize the relationship between these variables.

The design choice of using scatter plots with best-fit lines was made to accurately depict the trends and correlations between the variables.

### 3. Limitations of Paired Data Visualizations

Paired data visualizations were deemed unsuitable for the roller coaster dataset due to the independent nature of the variables. The categorical variables such as roller coaster names, theme park names, and track types do not have a direct numerical relationship with other variables. Additionally, while numerical variables such as speed, height, drop size, length, duration, and inversions may exhibit correlations, they do not constitute paired measurements or observations in the traditional sense.

### 4. Paired Data Visualization with Bike Share Data

A paired scatter plot and a slope graph were created using data from the bikeshare.txt dataset, which contains paired measurements of bike share users across different seasons.

The paired scatter plot depicted the count of users against seasons, while the slope graph illustrated the trends in user counts, differentiating between casual and registered users.

The slope graph was preferred over the paired scatter plot due to its effectiveness in highlighting trends and changes over categories, such as seasons, and its ability to facilitate a straightforward comparison between different user types.

In summary, the choice between a paired scatter plot and a slope graph depends on the nature of the data and the specific insights being sought. While a paired scatter plot is suitable for direct comparisons between two variables, a slope graph is better suited for visualizing trends and changes over categories or time periods.
