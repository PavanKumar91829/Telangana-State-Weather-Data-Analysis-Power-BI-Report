# Telangana State Weather Data Analysis

## Overview
This project analyzes historical weather data from various districts and mandals in Telangana. The dataset includes key weather parameters such as rainfall, temperature, humidity, and wind speed, along with additional derived metrics for in-depth insights. The data was cleaned and enhanced by adding new columns using DAX.

## Dataset Structure
The dataset is taken from Telangana State Weather Department.

The weather dataset is organized into four folders corresponding to the years:
- **2021**
- **2022**
- **2023**
- **2024**

Combined all folders contains **38 files**, providing comprehensive data for each respective year.
## Dataset Details
- **Initial dataset:** 7,20,527 rows and 10 columns
- **Cleaned dataset:** 7,04,388 rows and 17 columns
- **Added columns:**
  - `Season`
  - `DailyTemperatureRange`
  - `Daily Humidity Range`
  - `Daily WindSpeed Range`
  - `HighRainfallFlag`
  - `HighTempFlag`
  - `LowTempFlag`

## Data Description
| Column Name            | Description                                    |
|------------------------|------------------------------------------------|
| `District`             | District where data was recorded               |
| `Mandal`               | Localized area within the district             |
| `Date`                 | Date of observation                            |
| `Rain (mm)`            | Rainfall measured in millimeters               |
| `Min Temp (℃)`         | Minimum temperature recorded                   |
| `Max Temp (℃)`         | Maximum temperature recorded                   |
| `Min Humidity (%)`     | Minimum humidity recorded                      |
| `Max Humidity (%)`     | Maximum humidity recorded                      |
| `Min Wind Speed (Kmph)`| Minimum wind speed recorded                    |
| `Max Wind Speed (Kmph)`| Maximum wind speed recorded                    |

## Analysis

### Rainfall Analysis
- Identify the district with the highest average rainfall.
- Analyze monthly rainfall distribution across mandals.
- Examine rainfall trends over the years.
- Study seasonal rainfall variations across districts.
- Investigate rainfall patterns on specific dates.
- Compare annual rainfall between two districts.
- Detect periods of high rainfall intensity.
- Identify rainfall anomalies over the years.
- Determine monthly rainfall contributions to annual totals.

### Temperature Insights
- Compute average minimum and maximum temperatures for each district.
- Study seasonal temperature variations in mandals.
- Identify temperature anomalies over the years.
- Analyze daily temperature range per district.
- Examine trends in minimum and maximum temperatures.
- Identify periods of extreme temperatures.
- Assess temperature distribution throughout the year.
- Compare temperature patterns between two districts.
- Analyze correlation between minimum and maximum temperatures.

### Humidity Patterns
- Compare average minimum and maximum humidity across districts.
- Study seasonal humidity changes in mandals.
- Identify anomalies in humidity levels over the years.
- Analyze daily humidity range per district.
- Examine trends in minimum and maximum humidity.
- Identify periods of extreme humidity.
- Study humidity distribution throughout the year.
- Compare humidity patterns between two districts.
- Explore how humidity variations affect health outcomes (if data available).

### Wind Speed Analysis
- Compute average minimum and maximum wind speeds per district.
- Study annual wind speed variations in mandals.
- Identify significant wind speed patterns or outliers.
- Analyze daily wind speed range per district.
- Examine trends in wind speeds over the years.
- Identify periods of extreme wind speeds.
- Study wind speed distribution throughout the year.
- Compare wind speed patterns between two districts.
- Assess the impact of wind speed variations on daily activities.

### Comprehensive Weather Insights
- Develop a dashboard with key weather metrics per district.
- Analyze correlations between rainfall, temperature, humidity, and wind speed.
- Identify extreme weather events and their impact.
- Examine long-term trends in weather metrics.
- Detect seasonal patterns in weather data.
- Compare overall weather patterns between two districts.
- Identify anomalies in the dataset.
- Study the distribution of key weather metrics throughout the year.


