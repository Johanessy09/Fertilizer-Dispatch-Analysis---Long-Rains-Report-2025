# Fertilizer Dispatch Analysis - Long Rains Report 2025

## Overview
This repository contains the analysis and visualization of fertilizer dispatch data provided by the **National Cereals and Produce Board (Kenya)**. The dataset is based on the **Long Rains Fertilizer Dispatch Report** as of **11th March 2025**.

### Goals
- Clean and preprocess the data for analysis.
- Identify patterns and trends in fertilizer dispatches across counties.
- Visualize key insights through different types of plots.

---

## Dataset
The dataset is stored in a CSV file named `fertilizer.csv`. It includes the following columns:

- `County`
- `Planting Fertiliser`
- `Top Dressing Fertiliser`
- `Total Dispatches`
- `Percentage %`

The data captures the quantities of fertilizers dispatched to various counties, their total, and their percentage distributions.

---

## Project Workflow

### 1. **Data Cleaning**
- Rows containing invalid or missing values were handled.
- The summary row labeled `'TOTAL'` was excluded from analysis.

### 2. **Exploratory Data Analysis (EDA)**
- Summary statistics of the data were generated to understand the distribution of numerical columns.
- Relationships between planting and top-dressing fertilizers were explored.

### 3. **Visualizations**
- **Bar Graph:** Total dispatches per county.
- **Pie Chart:** Percentage distribution of dispatches per county (optional).
- **Scatter Plot:** Comparison of planting and top-dressing fertilizer quantities.
- **Heatmap:** Correlation among numerical columns.
- **Interactive Bar Chart:** Visualization using Plotly for dynamic exploration.
  

## Data Source
The dataset is sourced from the **National Cereals and Produce Board (Kenya)** as part of the **Long Rains Fertilizer Dispatch Report (11th March 2025)**.
