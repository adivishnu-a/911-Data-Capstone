# 911 Calls Capstone Project

This repository contains a capstone project analyzing 911 call data from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The data includes various fields such as latitude, longitude, description of the emergency call, zipcode, title, timestamp, township, address, and a dummy variable.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Setup and Installation](#setup-and-installation)
- [Data Analysis](#data-analysis)
  - [Basic Questions](#basic-questions)
  - [Creating New Features](#creating-new-features)
  - [Data Visualization](#data-visualization)
- [Heatmaps and Clustermaps](#heatmaps-and-clustermaps)
- [Conclusion](#conclusion)

## Project Overview

The goal of this project is to analyze 911 call data to gain insights into the most common reasons for calls, the distribution of calls over time, and to visualize the data using various plots and heatmaps.

## Data Description

The dataset contains the following fields:

- `lat`: Latitude
- `lng`: Longitude
- `desc`: Description of the Emergency Call
- `zip`: Zipcode
- `title`: Title
- `timeStamp`: Timestamp in the format YYYY-MM-DD HH:MM:SS
- `twp`: Township
- `addr`: Address
- `e`: Dummy variable (always 1)

## Setup and Installation

To run the notebook and perform the analysis, you need to have the following libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn plotly
```

## Data Analysis

### Basic Questions

- Top 5 Zipcodes for 911 Calls
- Top 5 Townships (twp) for 911 Calls
- Number of Unique Title Codes

### Creating New Features

- Extracting Reason from Title
- Most Common Reason for 911 Calls
- Converting `timeStamp` to DateTime
- Creating Hour, Month, and Day of Week Columns
- Mapping Day of Week to String Names

### Data Visualization

- Countplot of 911 Calls by Reason
- Countplot of 911 Calls by Day of Week
- Countplot of 911 Calls by Month
- Groupby Month and Plot
- Linear Fit on Number of Calls per Month
- Plotting Counts of 911 Calls by Date
- Separate Plots for Each Reason

## Heatmaps and Clustermaps

- Heatmap of Calls by Day of Week and Hour
- Clustermap of Calls by Day of Week and Hour
- Heatmap of Calls by Day of Week and Month
- Clustermap of Calls by Day of Week and Month

## Conclusion

This project provides a comprehensive analysis of 911 call data, including the most common reasons for calls, the distribution of calls over time, and various visualizations to better understand the data. The use of heatmaps and clustermaps helps to identify patterns and trends in the data, providing valuable insights for emergency response planning and resource allocation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset used in this project is from [Kaggle](https://www.kaggle.com/mchirico/montcoalert).
- Thanks to the contributors of the libraries used in this project: `numpy`, `pandas`, `matplotlib`, `seaborn`, and `plotly`.
