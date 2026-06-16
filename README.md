# Bellabeat Wellness Data Analysis

## Project Overview 
This project analyzes Fitbit smart device usage data to identify trends in physical activity, sleep habits and wellness behaviors. The findings provide actionable recommendations that could support Bellabeat's marketing and project strategies.
Bellabeat is a high-tech wellness company that develops smart products focused on women's health. Understanding how consumers use smart devices can help Bellabeat improve customer engagement and promote healthier lifestyles.

## Business Task
Analyze smart device fitness data to identify behavioral trends and generate insights that can support Bellabeat's future marketing decisions.

## Dataset
The analysis uses Fitbit Fitness Tracker Data made publicly available through Kaggle.
The datasets include information related to:
- Daily activity
- Step counts
- Calories burned
- Sleep records
- Weight logs
- Activity intensity levels
The data represents fitness tracker usage from consenting Fitbit users.

## Tools and Technologies
- R
-  RStudio
-  tidyverse
-  dplyr
-  ggplot2
-  Jupyter Notebook
-  GitHub

## Data Cleaning 
The following data preparation steps were performed:
- Imported multiple Fitbit datasets into R.
- Examined dataset structure and variable types.
- Removed duplicate records.
- Converted date and time columns into appropriate formats.
- Checked for missing values.
- Verified consistency across datasets.
- Merged datasets when necessary for analysis.

## Exploratory Data Analysis
The analysis focused on answering the following questions:
1. How active are Fitbit users?
2. How does physical activity relate to calories burned?
3. Are there differences in activity levels across weekdays?
4. What are users' sleep patterns?
5. How much time do users spend being sedentary?

## Visualizations
### Distribution of Activity Levels
This visualization illustrates the average amount of time users spend in different activity categories.

<img width="329" height="299" alt="activity_level_distribution" src="https://github.com/user-attachments/assets/db4244a5-017d-4efa-99d4-225f6959fbf0" />

**Insight:**
Most users spend a substantial portion of their day in sedentary activities, while very active minutes account for only a small percentage of total daily activity.

### Average Daily Steps by Weekday
This chart shows how average step counts vary throughout the week.

<img width="311" height="290" alt="average_steps_by_weekday" src="https://github.com/user-attachments/assets/1571864b-335e-4554-bdeb-939fc1cae975" />

**Insight:**
User activity differs across weekdays, indicating opportunities for Bellabeat to tailor engagement strategies according to behavioral patterns.

### Steps vs Calories Burned
This scatter plot examines the relationship between daily steps and calories burned.

<img width="340" height="302" alt="steps_vs_calories" src="https://github.com/user-attachments/assets/6d66152a-4841-4e42-aa25-15c2b44b297e" />

**Insight:**
Higher daily step counts are generally associated with greater calorie expenditure, highlighting the benefits of maintaining an active lifestyle.

### Distribution of Sedentary Minutes
The visualization of displays how much time users spend being sedentary.

<img width="330" height="305" alt="sedentary_minutes_distribution" src="https://github.com/user-attachments/assets/939cf944-b6ae-4664-ac30-638fb780b48b" />

**Insight:**
Many users exhibit high levels of sedentary behavior, suggesting an opportunity for Bellabeat to encourage more frequent movement. 

## Key Findings 
- Users spend a large portion of their day sedentary.
- Increased physical activity is associated with higher calorie expenditure.
- Daily activity levels vary throughout the week.
- Most users engage in limited amounts of vigorous activity.
- Behavioral data can be used to promote healthier habits and improve user engagement.

## Recommendations
Based on the analysis, Bellabeat should consider:
1. Encouraging users to increase daily movement through personalised  activity goals.
2. Sending reminders to reduce prolonged sedentary behavior.
3. Delivering motivational insights based on weekly activity trends.
4. Promoting achievable wellness challenges to improve consistency.
5. Leveraging user behavior data to provide personalized recommendations.

## Repository Structure

```text
bellabeat-analysis
│
├── data/
├── scripts/
├── visualizations/
├── README.md
```

## Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- Statistical Interpretation
- R programming
- GitHub Documentation

## Author 
**Sneha Pirahalathan**

Google Data Analytics Portfolio Project
