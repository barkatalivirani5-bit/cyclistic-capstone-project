# Cyclistic Bike-Share Capstone Project

## 📊 Google Data Analytics Capstone

This repository contains my analysis for the Cyclistic bike-share case study, completed as part of the Google Data Analytics Professional Certificate. The goal of this project is to analyze how annual members and casual riders use Cyclistic bikes differently and provide data-driven recommendations for converting casual riders to annual members.

## 📁 Repository Structure
├── scripts/ # R scripts for analysis
│ ├── 01_data_cleaning.R # Data import and cleaning
│ ├── 02_analysis.R # Exploratory data analysis
│ └── 03_visualizations.R # Creating charts and graphs
├── visualizations/ # Generated plots
│ ├── ride_duration_by_member_type.png
│ ├── rides_by_day_of_week.png
│ └── monthly_usage_patterns.png
├── documentation/ # Final report
│ └── cyclistic_presentation.pdf
└── README.md # Project overview

## 📈 Data

The dataset used in this analysis contains Cyclistic trip data from [Month Year] to [Month Year]. The original data was provided by Motivate International Inc. under this [license](https://www.divvybikes.com/data-license-agreement).

The cleaned dataset used in this analysis is **too large for direct GitHub storage** and is available as a **GitHub Release**:

➡️ **[Download the Cleaned Dataset Here](https://github.com/YOUR-USERNAME/cyclistic-capstone-project/releases/latest)** ⬅️

### Data Processing Steps:
1. **Data Import**: Combined 3 months each of trip data 2019 and 2020 into a single dataframe
2. **Data Cleaning**: 
   - Removed rows with null values
   - Filtered out test stations and invalid ride IDs
   - Removed negative ride durations
3. **Feature Engineering**:
   - Calculated ride duration in minutes
   - Extracted day of week, month, hour from start time
   - Created season and time-of-day categories

## 🔍 Analysis Overview

### Business Question
**How do annual members and casual riders use Cyclistic bikes differently?**

### Analysis Approach
I followed the Google Data Analytics process:
1. **Ask**: Define the business question and stakeholder requirements
2. **Prepare**: Collect and organize the trip data
3. **Process**: Clean and transform the data for analysis
4. **Analyze**: Perform statistical analysis and identify patterns
5. **Share**: Create visualizations to communicate findings
6. **Act**: Provide recommendations based on insights

### Key Metrics Analyzed
- Average ride duration by member type
- Number of rides per day of week
- Monthly usage patterns
- Peak usage hours
- Starting station preferences
- Bike type preferences

## 📝 Key Findings

### 1. **Usage Patterns by Day of Week**
- **Casual riders** show peak usage on weekends (Saturday and Sunday), suggesting recreational use
- **Annual members** have consistent high usage on weekdays, indicating commuting behavior

### 2. **Ride Duration Differences**
- **Casual riders** take significantly longer rides (average 25-30 minutes) compared to members (12-15 minutes)
- This suggests casual riders use bikes for leisure while members use them for efficient transportation

### 3. **Seasonal Trends**
- Both user types show increased ridership during summer months (June-August)
- Casual rider activity drops more dramatically in winter months
- Members maintain more consistent year-round usage

### 4. **Peak Usage Times**
- **Members**: Peak during commute hours (7-9 AM and 4-6 PM weekdays)
- **Casual riders**: Peak during afternoon hours (12-5 PM) on weekends

## 💡 Recommendations

Based on these findings, I recommend the following strategies to convert casual riders to annual members:

1. **Weekend Membership Promotions**: Target casual riders on weekends with special membership offers
2. **Loyalty Program**: Create a "frequent rider" program that rewards casual riders with membership credits
3. **Seasonal Passes**: Offer winter discounts to maintain engagement during low-usage months
4. **Educational Campaign**: Show casual riders the cost savings of annual membership compared to casual passes
5. **Weekend Events**: Host member-only weekend events to showcase the social benefits of membership

## 🛠️ Tools Used

- **R Programming Language**: Primary analysis tool
- **tidyverse**: Data manipulation and transformation
- **ggplot2**: Creating visualizations and charts
- **lubridate**: Date and time processing
- **dplyr**: Data aggregation and summary statistics
- **knitr**: Report generation

## 📊 Visualizations

Key visualizations included in this analysis:
- Bar charts comparing ride counts by member type and day of week
- Box plots showing ride duration distribution
- Line graphs tracking monthly usage trends
- Heat maps of usage by hour and day

## 📄 License

This project is for educational purposes as part of the Google Data Analytics Certificate program. The data is provided by Motivate International Inc. under this [license](https://www.divvybikes.com/data-license-agreement).

## 📬 Contact
Email: barkatali.virani5@gmail.com
Barkatali Virani - [@barkatalivirani5-bit](https://github.com/barkatalivirani5-bit)
Project Link: [https://github.com/barkatalivirani5-bit/cyclistic-capstone-project](https://github.com/barkatalivirani5-bit/cyclistic-capstone-project)
