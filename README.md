# Managed WiFi Dashboard and Reports

## Overview

This repository contains the documentation for the Managed WiFi solution developed for our client. The solution involves collecting data from APIs every 6 minutes using Python scripts, performing data modeling to identify key metrics, and creating a dashboard in Power BI to visualize the collected data. The dashboard includes information about the number of installed Access Points (APs), unique zones, currently connected clients, total Network Access Server (NAS) information, RSSI, traffic Signal-to-Noise Ratio (SNR), and radio connection bifurcation between 2.4 GHz and 5 GHz bands. Client-level information is also visualized for better insights.

## Folder Structure

- **/scripts**: Contains Python scripts used to collect data from the APIs.
- **/data**: Stores the collected data and any intermediate files.
- **/data_modeling**: Includes scripts and notebooks for data modeling and identification of key metrics.
- **/dashboard**: Holds files related to the Excel dashboard.
- **/presentation**: Contains the PowerPoint presentation.

## Usage

### Data Collection

1. Run the Python script located in the `/scripts` directory to collect data from the APIs. The script automatically fetches data every 6 minutes.
2. The collected data will be saved in the `/data` directory.

### Data Modeling

- Detailed information about the data modeling process can be found in the Jupyter Notebooks located in the `/data_modeling` directory.

### Dashboard

- Access the Excel dashboard by opening the dashboard file located in the `/dashboard` directory. The dashboard provides visual insights into various WiFi metrics, including AP installations, unique zones, connected clients, NAS information, RSSI, SNR, and radio connections.

## Dependencies

- Python 3.x for collecting data from API
- Excel and Power BI (for data modeling)
- Power Bi (for viewing/editing the dashboard)

## Contributors

- [Ankur Srivastava]

