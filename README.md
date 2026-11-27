# Food Delivery Data Analysis

# Project Overview

This project focuses on cleaning, exploring, and analyzing a food delivery dataset using Python.

The objective is to understand the dataset, identify data quality issues, perform data cleaning, and conduct Exploratory Data Analysis (EDA) to discover factors affecting food delivery time.

The project is divided into two stages:

# Week 1: Data Understanding and Cleaning
# Week 2: Exploratory Data Analysis (EDA)

# Tools and Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Git and GitHub
Dataset Information
Total records: 45,584
Total columns: 20
Duplicate rows: 0
Duplicate IDs: 0
Missing values after cleaning: 9,184
Each row represents a food delivery record.

# Week 1: Data Cleaning

The following data cleaning tasks were performed:

Removed leading and trailing whitespace.
Corrected city spelling inconsistencies.
Converted Order_Date into datetime format.
Standardized order and pickup time representations.
Checked numeric values and rating ranges.
Identified and retained missing values where no justified replacement was available.
Checked duplicate rows and IDs.
Outcome: The cleaned dataset was exported as cleaned_food_delivery.csv.

# Week 2: Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand relationships between delivery time and different factors.

Analysis Performed
Delivery time distribution
Traffic conditions analysis
Weather conditions analysis
Vehicle type analysis
Multiple deliveries analysis
Customer ratings analysis
Key Findings
1. Traffic Analysis

Jam traffic had the highest average delivery time: 31.18 minutes.
Low traffic had the lowest average: 21.27 minutes.
The difference was approximately 9.91 minutes.
2. Weather Analysis

Cloudy weather had an average delivery time of 28.92 minutes.
Sunny weather had the lowest average: 21.86 minutes.
The difference was approximately 7.06 minutes.
3. Vehicle Analysis

Motorcycles had the highest average delivery time: 27.61 minutes.
Electric scooters had an average of 24.47 minutes.
4. Multiple Deliveries Analysis

Zero additional deliveries: 22.88 minutes average.
One additional delivery: 26.85 minutes.
Two additional deliveries: 40.45 minutes.
Three additional deliveries: 47.82 minutes.
Delivery time increased as the number of additional deliveries increased.

5. Ratings Analysis

Ratings of 4.8 were the most common.
Lower customer ratings generally appeared alongside longer delivery times.
Project Structure
food-delivery-data-analysis/
│
├── 01_data_understanding_and_cleaning.ipynb
├── Eda.ipynb
├── cleaned_food_delivery.csv
├── README.md
├── requirements.txt
│
└── visualizations/
    ├── multiple_deliveries.png
    ├── ratings_analysis.png
    ├── traffic_analysis.png
    ├── vehicle_analysis.png
    └── weather_analysis.png

# Project Outcomes

Cleaned and prepared 45,584 food delivery records.
Performed exploratory analysis on important delivery factors.
Identified patterns between traffic, weather, vehicle type, multiple deliveries, customer ratings, and delivery time.
Created visualizations to communicate analytical findings.

## Week 3: Data Visualization and Analysis

### Objective
The objective of Week 3 was to visualize the cleaned Food Delivery dataset and identify patterns affecting delivery duration.

### Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Visualizations

**1. Delivery Duration Distribution**

A histogram was created to understand the distribution of food delivery times.

![Delivery Duration Distribution](visualizations/01_delivery_duration_distribution.png)

**2. Traffic Comparison**

A bar chart was created to compare median delivery duration across traffic categories.

![Traffic Comparison](visualizations/02_traffic_comparison.png)

**3. Weather Comparison**

A bar chart was created to compare average delivery duration across weather conditions.

![Weather Comparison](visualizations/03_weather_comparison.png)

**4. Distance vs Delivery Duration**

A scatter plot was created to investigate the relationship between delivery distance and delivery time. Records with calculated distances above 50 km were excluded from this visualization.

![Distance vs Delivery Duration](visualizations/04_distance_vs_duration.png)

**5. Vehicle Comparison**

A box plot was created to compare delivery duration across different vehicle types.

![Vehicle Comparison](visualizations/05_vehicle_comparison.png)

### Key Findings
- Jam traffic had the highest median delivery duration of 31 minutes.
- Low traffic had the lowest median delivery duration of 20 minutes.
- Cloudy weather had the highest average delivery duration ossf 28.92 minutes.
- Sunny weather had the lowest average delivery duration of 21.86 minutes.
- Motorcycle deliveries had the highest average duration of 27.61 minutes.

### Conclusion
The visualizations helped identify patterns in delivery duration based on traffic, weather, distance, and vehicle type. This analysis provides useful insights into food delivery performance.

# Author
Mohsin Saad