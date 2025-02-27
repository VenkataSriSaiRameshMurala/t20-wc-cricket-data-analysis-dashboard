# ICC Men's T20 Cricket World Cup 2022 Data Analysis

# Overview
This project focuses on analyzing the ICC Men's T20 Cricket World Cup 2022 using Power BI. The dashboard provides insights into team and player performances, helping cricket enthusiasts and analysts review statistics, compare players, and even determine the best XI based on key performance indicators.

# Table of Contents
1. Problem Statement
2. Data Collection & Sources
3. Data Preparation & Transformation
4. Data Modeling
5. Key Metrics & DAX Calculations
6. Dashboard & Insights
7. Tools & Technologies Used

# Problem Statement
The objective of this project is to create a Power BI dashboard that enables a detailed analysis of the T20 World Cup 2022. This includes evaluating individual player performances, comparing batting and bowling stats, and identifying top performers across different roles such as openers, middle-order batsmen, all-rounders, and bowlers.

# Data Collection & Sources
The data for this analysis was gathered from multiple sources, including match statistics and player performance records. The raw data was stored in various formats such as CSV and JSON files before being processed for analysis.

# Data Preparation & Transformation
Once the raw data was collected, it was cleaned and transformed for better usability. This included:

1.Standardizing player names and correcting inconsistencies
2.Handling missing values and ensuring data integrity
3.Establishing relationships between datasets based on match and player IDs
4.Formatting the data for smooth integration into Power BI

Power Query was extensively used to clean and shape the data before loading it into Power BI for visualization.

# Data Modeling
To ensure seamless analysis, relationships were established between different datasets. Primary keys such as match IDs and team names were used to connect data tables, enabling dynamic filtering and deeper insights. Several calculated columns and measures were also created using DAX (Data Analysis Expressions) to enhance the analysis.

# Key Metrics & DAX Calculations
A variety of DAX measures were used to compute important cricketing statistics, including:
1.Batting Metrics: Total runs, strike rate, batting average, boundary percentage, and batting position
2.Bowling Metrics: Wickets taken, economy rate, bowling average, and dot ball percentage
3.Team Performance Metrics: Win/loss analysis, run rate comparisons, and team rankings

# Dashboard & Insights
The Power BI dashboard provides an interactive visualization of key performance indicators. It includes:

1.Player performance analysis categorized by role (Openers, Middle Order, Finishers, All-Rounders, and Bowlers)
2.Comparison of key batting and bowling statistics
3.Selection of the best XI based on statistical performance
4.Team-wise performance breakdown

# Tools & Technologies Used
1.Python for initial data handling
2.Pandas for data cleaning and transformation
3.Power BI for visualization and dashboard creation
4.Power Query for data transformation
5.DAX for advanced calculations and measures

# Conclusion
This project demonstrates the power of data analytics in sports by providing a comprehensive and interactive way to analyze cricketing performance. With this dashboard, users can easily explore statistics, compare player performances, and gain deeper insights into the T20 World Cup 2022.

