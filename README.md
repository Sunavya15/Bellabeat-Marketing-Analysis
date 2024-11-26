# Bellabeat-Marketing-Analysis
Data analysis on Bellabeat's marketing strategy using Fitbit data.
# Bellabeat Marketing Analysis

In this project, I analyze Fitbit data to provide insights into Bellabeat's customer activity and sleep patterns. The goal is to understand how different activity levels (based on steps taken) correlate with sleep habits, such as sleep duration and time spent in bed. These insights will help guide marketing strategies for Bellabeat products.

## Project Overview

Bellabeat is a wellness technology company that manufactures health-focused products, and this project focuses on analyzing Fitbit data to uncover patterns in user activity and sleep. Using the cleaned Fitbit data, I explore how users' activity levels (based on total steps) influence their sleep duration and time spent in bed. These insights can help Bellabeat in tailoring their marketing strategies for their wellness products.

## Data Sources

- **Fitbit Activity Data**: Data containing users' daily activity metrics, such as total steps, calories burned, and activity levels.
- **Fitbit Sleep Data**: Data detailing users' sleep habits, including the total minutes asleep and total time in bed.

Both datasets are publicly available through the Kaggle dataset repository.

## Data Cleaning & Preprocessing

- **Missing Values**: The data was cleaned by removing rows with missing values and replacing missing numeric values with the mean.
- **Date Conversion**: Date columns (`ActivityDate`, `SleepDay`) were converted to `Date` type for proper analysis.
- **Activity Level Categorization**: Activity levels were categorized as "Low", "Medium", and "High" based on the total steps taken.

## Data Visualizations

This project includes the following key visualizations:

1. **Steps vs Sedentary Minutes (Scatter Plot)**:
   - Shows the relationship between physical activity (steps) and sedentary behavior (sedentary minutes).
   
2. **Minutes Asleep vs Time in Bed (Scatter Plot)**:
   - Displays the connection between the total minutes asleep and the total time spent in bed.

3. **Sedentary Minutes by Activity Level (Box Plot)**:
   - Visualizes the distribution of sedentary minutes across different activity levels (Low, Medium, High).

4. **Steps vs Calories Burned (Scatter Plot)**:
   - Illustrates how the number of steps correlates with the number of calories burned, highlighting the fitness benefits.

## Key Findings

- **Activity vs Sedentary Minutes**: Active individuals tend to spend fewer minutes sedentary, indicating the importance of promoting Bellabeat products for reducing sedentary behavior.
- **Sleep and Time in Bed**: There is a strong correlation between time in bed and sleep duration, which suggests that Bellabeat can focus on promoting products that help optimize sleep quality.
- **Activity Levels**: Users in the "Low Activity" category have significantly higher sedentary minutes, suggesting an opportunity for Bellabeat to target these users with products that encourage more physical activity.

## Conclusion

The analysis indicates that Bellabeat can use insights from customer activity and sleep patterns to create targeted marketing strategies. Promoting the benefits of physical activity, improving sleep quality, and providing personalized recommendations based on activity levels can help increase customer engagement with Bellabeat products.

## Repository Structure

- `Bellabeat.Rmd`: R Markdown file containing the full analysis and code.
- `Bellabeat.html`: HTML file generated from the R Markdown file (with analysis results and visualizations).
- `data/`: Folder containing the raw data files used for analysis.

## Future Work

Future analyses could explore other factors influencing activity and sleep patterns, including diet, stress, and age, to further refine marketing strategies. Additionally, integrating more data sources could enhance the precision of personalized recommendations.
