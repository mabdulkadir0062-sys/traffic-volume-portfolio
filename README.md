# traffic-volume-portfolio

## 📊 Project Overview

### This project analyzes traffic volume patterns using real-world-style road network data to uncover how road class, lane capacity, and direction influence traffic flow and speed limits over time.

## 🎯 Business Problem

### Urban planners and transportation agencies need to understand:

. How traffic volume varies by road type

. Whether lane capacity influences traffic flow efficiency

. How traffic patterns evolve over time

This analysis helps support decisions in:

. Road infrastructure planning

. Traffic optimization strategies

. Smart city development

## Data Cleaning & Preparation

### Key transformation applied :

. Standardized categorical text fields (uppercase + trimmed)

. Converted date strings into datetime format

. Casted numerical columns into optimized integer types

. Removed redundant columns 

. Handled missing values by removing incomplete rows

## 📊 Visualizations

 ### The project includes:

. Grouped bar charts 

. Scatter plots 

. Time series analysis

All visualizations were built using Plotly for interactivity and exploratory analysis.

## 🧠 Skills Demonstrated

### theese skills are :

. Data cleaning and transformation

. Feature engineering

. Group-by aggregation analysis

. Interactive data visualization

. End-to-end analytics workflow

## Key Insighst 

### 1- Distribution of Traffic Volume by Road Class & Flow Direction

. Arterial roads carry the highest traffic volumes, significantly above Collector and Local Streets

. Collector roads act as mid-level connectors, handling moderate traffic

. Local Streets consistently carry very low traffic, mainly serving access functions

- Insight: A clear and stable urban traffic hierarchy exists where Arterials dominate mobility, Collectors distribute flow, and Local Streets serve local access

  ### 2- Correlation Between Lane Capacity & AADT

. Higher lane counts strongly increase traffic volume mainly on Arterial roads

. Collector roads show moderate and inconsistent scaling with lane increases

. Local Streets show minimal impact from lane expansion, remaining low-volume regardless of capacity

- Insight: Lane expansion is most effective on high-capacity roads (Arterials), while lower-tier roads are influenced more by function than physical capacity

  ### 3- Evolution of Traffic Volumes by Road Class

 . Arterial roads consistently maintain the highest traffic across all years, with noticeable growth in recent decades
 
. Collector roads remain stable mid-level carriers over time

. Local Streets stay consistently low-volume, with minor fluctuations only

- Insight: Over time, traffic growth is primarily absorbed by Arterial infrastructure, while the overall road hierarchy remains stable and unchanged
