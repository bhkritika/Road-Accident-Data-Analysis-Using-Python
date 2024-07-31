# Road Accident Data Analysis Using Python

## Overview

This project focuses on analyzing road accident data to uncover trends, patterns, and insights related to accidents. The dataset includes various features such as accident severity, casualty details, and vehicle information. The goal is to identify key factors influencing accidents and provide actionable recommendations for improving road safety.

## Dataset

The dataset contains the following columns:

- `collision_index`: Unique identifier for the accident
- `collision_year`: Year of the accident
- `collision_reference`: Reference code for the collision
- `vehicle_reference`: Reference code for the vehicle involved
- `casualty_reference`: Reference code for the casualty involved
- `casualty_class`: Classification of the casualty
- `sex_of_casualty`: Gender of the casualty
- `age_of_casualty`: Age of the casualty
- `age_band_of_casualty`: Age band of the casualty
- `casualty_severity`: Severity of the casualty
- `pedestrian_location`: Location of the pedestrian involved
- `pedestrian_movement`: Movement of the pedestrian involved
- `car_passenger`: Number of car passengers involved
- `bus_or_coach_passenger`: Number of bus or coach passengers involved
- `pedestrian_road_maintenance_worker`: Number of road maintenance workers involved
- `casualty_type`: Type of casualty
- `casualty_home_area_type`: Type of home area of the casualty
- `casualty_imd_decile`: IMD decile of the casualty
- `lsoa_of_casualty`: LSOA (Lower Layer Super Output Area) of the casualty

## Analysis

### 1. **Accident Trends Over Time**

- Analyzed the number of accidents over the years.
- Identified trends and patterns in accident frequency.

### 2. **Casualty Severity Analysis**

- Examined the distribution of casualty severity.
- Identified factors contributing to higher severity.

### 3. **Impact of Demographic Factors**

- Analyzed casualty data by age and gender.
- Identified demographic groups most affected by severe accidents.

### 4. **Geospatial Insights**

- Conducted geospatial analysis to identify high-risk areas.
- Created heatmaps to visualize accident concentrations.

### 5. **Vehicle and Casualty Characteristics**

- Analyzed the relationship between vehicle types and casualty characteristics.
- Identified key factors associated with higher accident rates.

### 6. **Predictive Modeling**

- Built and evaluated predictive models to classify accident severity.
- Assessed model performance and accuracy.

## Visualizations

- **Accident Trends Over Years**: Line plot showing trends in accident numbers.
- **Casualty Severity Distribution**: Bar chart displaying the severity distribution.
- **Age and Gender Analysis**: Plots depicting the relationship between age, gender, and accident severity.
- **Heatmap of Accidents by Location**: Geospatial heatmap showing accident hotspots.

## Recommendations

1. **Enhanced Safety Measures**: Implement targeted safety measures in high-risk areas and for affected demographic groups.
2. **Policy Adjustments**: Consider policy changes based on accident trends and severity distributions.
3. **Public Awareness Campaigns**: Launch campaigns to educate the public on safe driving practices.
4. **Further Research**: Explore additional factors like weather conditions and traffic volume.
5. **Regular Monitoring**: Establish regular monitoring of accident data to adapt strategies.

## Future Work

- Explore the impact of external factors such as weather and time of day.
- Integrate additional datasets for a more comprehensive analysis.
- Develop interactive dashboards for dynamic exploration of data.

## Getting Started

To run the analysis, clone this repository and follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/road-accident-data-analysis.git
2. **Navigate to the Project Directory**
   cd road-accident-data-analysis
3. **Install Dependencies**
   pip install -r requirements.txt
4. **Run the Analysis**
   Execute the Jupyter notebooks or Python scripts provided in the notebooks and scripts directories.

## Files
- `data/` - Contains the dataset used for analysis.
- `notebooks/` - Jupyter notebooks with detailed analysis and visualizations.

