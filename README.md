# Purwadhika-Sales-Admission

## Overview

Purwadhika is a renowned digital bootcamp in Indonesia, established in 1987, with a strong focus on admissions and sales. Prior to 2023, sales and chat data were not utilized for customer analysis. With the integration of Mekari Qontak Omnichannel, we now have the capability to extract and analyze chat data to gain insights into customer behavior and agent performance. This includes understanding preferred branches, products, reply times, and identifying sales leads. 

This project involves cleaning, extracting, and visualizing chat data in Tableau for daily monitoring. The admissions team can now track previously unassigned chats and follow up on warm or hot leads to enhance sales conversions. 

### Impact

The analysis has led to significant restructuring within the Admissions team:
- **Promotion**: A supervisor has been promoted to oversee agents' quality.
- **Expansion**: Two new team members have been added to the team.
These changes have resulted in improved sales conversions and enhanced business metrics.

## Features

- **Data Cleaning**: Clean and preprocess the chat data.
- **Data Visualization**: Visualize the cleaned data in Tableau for actionable insights.
- **Sales Monitoring**: Track customer interactions, preferred branches, products, and identify leads.
- **ETL Pipeline**: Automate data handling with an ETL pipeline:
  - **Extract**: Retrieve data from Google Drive using Google API.
  - **Transform**: Process and transform the raw data.
  - **Load**: Upload the transformed data back to Google Drive.

## Getting Started

### Prerequisites

- Tableau for data visualization.
- Mekari Qontak Omnichannel for chat data extraction.
- Google Drive and Google API for ETL pipeline.
