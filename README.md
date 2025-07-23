# Social Media Engagement Analysis

This repository contains a Python script for analyzing social media engagement data. The script loads social media post data, performs SQL-based aggregations, calculates key performance indicators (KPIs), and visualizes engagement trends and breakdowns.

## Project Structure

-   `social_media_analysis.py`: The main Python script containing all the code for data loading, SQL analysis, and visualization.
-   `README.md`: This file.

## Features

-   **Data Loading & Preparation:** Reads embedded CSV data into a pandas DataFrame and performs initial data cleaning and feature engineering (e.g., `total_engagement`).
-   **SQL-based Analysis:** Utilizes SQLite to perform aggregations and calculate average engagement metrics by platform and campaign. Also calculates overall KPIs like engagement rate, average engagement per post, share rate, and comment rate.
-   **Data Visualization:** Generates informative plots using Matplotlib and Seaborn, including:
    -   Total Engagement by Social Media Platform (Stacked Bar Chart)
    -   Daily Social Media Engagement Trend (Line Plot)
    -   Average Engagement by Post Type and Platform (Bar Plot)

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yeshwanthKumar-sa/Social-Media-Engagement-Analysis.git](https://github.com/yeshwanthKumar-sa/Social-Media-Engagement-Analysis.git)
    cd Social-Media-Engagement-Analysis
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```

3.  **Install the required Python packages:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
    *(Note: `sqlite3` is typically included with Python.)*

## How to Run

Execute the Python script from your terminal:

```bash
python social_media_analysis.py
