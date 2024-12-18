# User-Device-Behavior-Analysis

## Table of Outline

## [Project Description](#project-description)

## [Importance of the Project](#importance-of-the-project)

## [Potential Stakeholders](#potential-stakeholders)

## [Project Initialization](#project-initialization)

## [Key Insights](#key-insights)

## [Features Descriptions](#features-descriptions)

## [Data Preparation](#data-preparation)

## [Data Cleaning](#data-cleaning)

## [Data Transformation](#data-transformation)

## [Add calculated columns](#add-calculated-columns)

## [Data Model](#data-model)

## [Report Design](#report-design)


### Project Description:
---
Understanding how users interact with their devices is critical for improving user experience and optimizing app performance. This report provides insights into user behaviour patterns, such as app usage, battery consumption, and data usage, segmented by device type, operating system, age, and gender. It also categorizes users into behaviour classes, helping identify heavy or light users, which can guide product development and marketing strategies.

### Importance of the Project:
---
The analysis helps companies understand which devices and operating systems are more efficient or popular, allowing them to optimize their apps accordingly. It also aids in identifying user behaviour trends, providing valuable data for targeted marketing, product innovation, and improving customer satisfaction.

### Potential Stakeholders:
---
o **Product Managers**: To identify user preferences and optimize app features.

o **Marketing Teams**: For targeted campaigns based on user behaviour.

o **App Developers**: To optimize app performance on specific devices and operating systems.

o **Data Analysts**: To generate actionable insights from user behaviour data.

o **Customer Experience Teams**: To enhance user satisfaction by understanding pain points like high battery usage or excessive data consumption.

### Project Initialization
---
o **Project Title**: User Device Behaviour Analysis

o **Objective**: The goal of this Power BI report is to analyse user behaviour based on device usage, battery consumption, data usage, and categorize users based on their behaviour classes.

### Key Insights:
---
o Identify device usage patterns.

o Understand how different operating systems influence app usage and battery drain.

o Analyse behaviour trends by age and gender

### Features Descriptions
---
o **User ID**: A unique identifier for each user.

o **Device Model**: The model of the user's device.

o **Operating System**: The operating system the device runs on (e.g., android, iOS).

o **App Usage Time (hr/day)**: The total time spent using apps per day, in hours.

o **Screen on Time (hours/day)**: The time the device screen is on, in hours per day.

o **Battery Drain (mAh/day)**: The amount of battery consumed per day in milliampere-hour.

o **Number of Apps Installed**: The total number of apps installed on the device.

o **Data Usage (MB/day)**: Data consumed per day, in megabytes.

o **Age**: Age of the user.

o **Gender**: Gender of the user.

o **User Behaviour Class**: A categorical class representing user behaviour.

### Data Preparation
---
o Dataset: Import the provided CSV file (user_behavior_dataset.csv) into Power BI. (Storage Mode : Import)

### Data Cleaning:
---
o Ensured there are no missing or null values.

o Converted data types as needed (e.g., Age, App Usage Time, Battery Drain should be numeric).

### Data Transformation
---
o **Power Query Editor**:

o I Loaded the dataset and checked for duplicates or unnecessary columns.

### Add calculated columns:
---
o **Average App Usage per Hour**: Create a new column dividing App Usage Time by Screen on Time.

o **Data Usage per App**: Divide Data Usage (MB/day) by Number of Apps Installed.

### Data Model
---
The dataset has a simple structure with no relationships, so no additional tables or data model adjustments are required unless additional datasets are introduced later.

### Report Design
---
**Visuals**:

o **User Overview**:

o **Card Visual**: Display total number of users.

o **Pie Chart**: Breakdown by Gender.

o **Bar Chart**: Count of users by Operating System.

o **Device Usage Analysis**:

o **Column Chart**: Display average App Usage Time across different device models.

o **Clustered Bar Chart**: Show Battery Drain vs. Screen On Time by Device Model or Operating System.

![User Device Behavior Dashboard](https://github.com/user-attachments/assets/b5fc517c-5821-4589-9ec4-05755894dddd)

