# WK Performance Analysis

## Overview
This repository contains Python scripts for analyzing and calculating key performance metrics for "WK" services. These scripts process encounter data stored in CSV files, filter non-billable entries, compute revenue based on predefined billing rates, and track total client service hours.

## Features
- **Revenue Calculation:** Computes revenue across different service types using predefined billing rates.
- **Client Time Analysis:** Summarizes the total time spent with clients for each month.
- **Automated Data Processing:** Reads CSV files, filters relevant data, and performs calculations.
- **Error Handling:** Skips missing files without disrupting the execution.

## Prerequisites
To run the scripts, you need the following installed:
- Python (>=3.8)
- `pandas`
- `numpy`

You can install the required dependencies using:

```sh
pip install pandas numpy
