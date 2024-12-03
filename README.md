# Clustering Analysis of Police Calls for Service in San Jose

## Overview

This repository contains the implementation of clustering analysis performed on police call data from San Jose. The goal of the project is to uncover actionable insights to aid in resource allocation and public safety management through data-driven decision-making.

---

## Motivation

San Jose faces challenges related to increasing crime rates, growing urban populations, and limited police resources. This project seeks to optimize public safety planning by analyzing police call data using clustering techniques to identify patterns in call distribution.

---

## Objectives

- Analyze call distribution patterns using clustering techniques.
- Categorize incidents to support strategic decision-making.
- Provide insights for efficient resource allocation and proactive policing.

---

## Dataset

### Source
The dataset was sourced from the **San Jose Police Department Open Data Portal**.
- Dataset for 2022,2023,2024 can be downloaded from here - https://data.sanjoseca.gov/dataset/police-calls-for-service

### Dataset Preparation: Random Sampling of Rows

- To optimize performance and preserve dataset diversity, **5000 rows** were randomly sampled from each dataset using Python's `pandas` library.
- The code for generating the sampled datasets, along with the sampled data files, is included in the repository. Please ensure the correct file paths are specified when running the code.
- Files are named as : sampled_file2022.csv, sampled_file2023.csv and sampled_file2024.csv








### Description
- **Records**: 814,737 rows of police call data spanning 2022–2024.
- **Attributes**: The dataset includes the following key features:
  - **Date and Time**: Captures when the call was made.
  - **Location**: Addresses or intersections where incidents occurred.
  - **Call Type**: Nature of the incident (e.g., theft, vehicle stop, disturbance).
  - **Disposition**: Resolution status of the call.


---

## Implementation

### System Architecture
1. **Input**: Raw police call dataset.
2. **Preprocessing**:
   - Data cleaning, feature extraction, and normalization.
3. **Clustering**:
   - Applied K-Means, DBSCAN, and Hierarchical Clustering.
4. **Output**:
   - Insights into trends and visualizations for actionable strategies.

---

## How to Run the Jupyter Files

### Prerequisites
- Install Python 3.8+.
- Install Jupyter Notebook:
  ```bash
  pip install notebook
