# Real-time-process-monitoring-dashboard
Project Title: Real Time Process Monitoring Dashboard

## Authors:

Shiwani Bhagat, Barnali Das, Satendra Yadav

## Overview

This project is a real-time system monitoring dashboard built using Dash and Plotly. It helps track system performance by visualizing key metrics like CPU usage, memory usage, disk space, and running processes. The dashboard updates automatically every 2 seconds to provide live insights.

## Features
1. **CPU Usage** : 
* Displays a real-time graph of CPU utilization over time.

* Helps in monitoring system performance and detecting high CPU usage.

2.**Memory Usage** : 
* Shows a pie chart representing used and available memory.

* Useful for tracking how much RAM is currently occupied.

3.**Disk Usage** : 
* Visualizes storage utilization in a simple, easy-to-understand format.

* Displays the percentage of disk space used vs. available.

4.**Running Processes Table** : 
* Lists the top 10 processes consuming the most CPU power.

* Shows details like Process ID (PID), Name, CPU %, and Memory %.

## Technologies Used
* **Dash** (for building the web-based dashboard)

* **Plotly** (for visualizing system data)

* **Psutil** (for fetching real-time system performance data)

* **Pandas** (for processing and structuring data)

 ## How to Run the Dashboard
1**Install dependencies:**

* pip install dash psutil pandas plotly
  
**Run the application:**

* python app.py

**Open in browser:**

* http://127.0.0.1:8060
