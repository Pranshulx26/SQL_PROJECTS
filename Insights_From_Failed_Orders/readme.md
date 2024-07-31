# Insights from Failed Orders Project

Welcome to the "Insights from Failed Orders" project! This repository contains an in-depth analysis of order failures at Gett, a leading Ground Transportation Management platform. This project is designed to uncover the underlying causes of order failures and provide actionable insights to improve operational efficiency and customer satisfaction.

## Project Overview

Gett, formerly known as GetTaxi, operates a technology platform for corporate transportation management. The challenge is to analyze and understand why some orders fail, i.e., why clients do not get their requested rides. This project explores various aspects of order failures, including reasons, timing, and geographical distribution.

## Contents

- **`datasets/`**: Contains the dataset used for analysis.
- **`Failed_Orders_Analysis.ipynb`**: Jupyter Notebook with detailed analysis, visualizations, and findings.
- **`cvs_to_postgresql.ipynb`**: Notebook demonstrating the process of converting CSV data to PostgreSQL.
- **`rejection_map.html`**: Interactive HTML map visualizing the geographical distribution of failed orders.
- **`taxi.jpg`**: Sample image related to the project.

## Analysis

The project consists of the following key analyses:

1. **Distribution of Failure Reasons**:
   - Analyzed order failures based on cancellation reasons and system rejections.
   - Identified which category of failure is most prevalent.

2. **Hourly Failure Trends**:
   - Explored the distribution of failed orders by hour to identify peak failure times.
   - Analyzed if certain hours exhibit higher failure rates and provided explanations.

3. **Average Cancellation Time**:
   - Plotted the average time to cancellation with and without driver assignment.
   - Identified any outliers and drew conclusions regarding cancellation trends.

4. **ETA Distribution**:
   - Examined the distribution of average ETA (Estimated Time of Arrival) by hour.
   - Explained the implications of ETA variations on order failures.

5. **Geographic Distribution**:
   - Created an interactive map to visualize the geographical hotspots for order rejections.
   - Differentiated between client rejections and system rejections using different colors.

## Findings

- **Reasons for Failure**:
  - A significant portion of order failures is due to client cancellations before driver assignment.
  - System rejections are prominent and occur after longer waiting times.

- **Hourly Trends**:
  - Peak failure times align with high demand periods, indicating potential driver allocation issues.

- **Cancellation Time**:
  - Most client cancellations occur within the first few minutes, while system rejections are linked to longer wait times.

- **ETA Insights**:
  - Longer ETAs are associated with higher rejection rates, particularly during peak hours.

- **Geographic Insights**:
  - Certain areas have higher failure rates, both due to client cancellations and system rejections.

## Getting Started

To explore this project, clone the repository and open the Jupyter Notebooks:

```bash
git clone https://github.com/Pranshulx26/SQL_PROJECTS.git
cd SQL_PROJECTS
jupyter notebook
