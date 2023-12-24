# Diwali Sales Analysis

## Problem Statement

Over the recent years, both City Hotel and Resort Hotel have been grappling with elevated cancellation rates, leading to various challenges such as diminished revenues and suboptimal room utilization. Consequently, mitigating cancellation rates has become the primary objective for both hotels to enhance revenue generation efficiency. Our goal is to provide comprehensive business advice to address this issue. This report focuses on analyzing hotel booking cancellations and other factors unrelated to their core business and yearly revenue generation.

## Assumptions

1. No significant events occurred between 2015 and 2017 that would substantially impact the data used.
2. The information remains current and applicable for efficiently analyzing a hotel's potential plans.
3. There are no unforeseen drawbacks to the hotel implementing any recommended strategies.
4. The suggested solutions are not currently in use by the hotels.
5. The primary factor influencing income generation efficiency is booking cancellations.
6. Cancellations result in vacant rooms for the originally booked duration.
7. Clients make hotel reservations in the same year they cancel.

## Research Questions

1. What variables contribute to hotel reservation cancellations?
2. How can hotel reservation cancellations be minimized?
3. How can hotels be assisted in making pricing and promotional decisions?

## Hypothesis

1. Higher prices correlate with increased cancellation rates.
2. Longer waiting lists are associated with higher customer cancellation tendencies.
3. The majority of clients prefer making reservations through offline travel agents.

## Technologies Used

1. Python: Utilized as the programming language for data analysis and visualization.
2. Pandas: Used for data manipulation, cleaning, and analysis.
3. NumPy: Employed for numerical operations and array manipulations.
4. Matplotlib: Utilized for creating static visualizations, such as bar charts, line graphs, and pie charts.
5. Seaborn: Used for enhancing the aesthetics of Matplotlib plots and creating statistical data visualizations.

## Key Concepts Used

1. Data Cleaning and Preprocessing: Checked and handled missing values using isnull() and dropna(). Dropped unnecessary columns ('company', 'agent') that were not essential for the analysis.
2. Data Visualization: Utilized various types of plots, including bar charts, count plots, line graphs, and pie charts, for visualizing different aspects of hotel      booking data.
3. Descriptive Statistics: Used describe() to obtain summary statistics for the dataset, both for numerical and categorical columns.
4. Date Formatting: Formatted the date column ('reservation_status_date') using pd.to_datetime().
5. Grouping and Aggregation: Grouped data by specific columns (e.g., 'reservation_status_date', 'month') and performed aggregations using groupby().

