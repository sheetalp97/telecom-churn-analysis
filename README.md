# Telecom Churn Analysis

## Overview

This project analyzes customer churn in the telecom industry. The goal is to understand the factors that contribute to churn and develop a predictive model to identify customers at high risk of leaving. This analysis is based on the "Telecom Churn Case Study" dataset. This project was completed as part of a case study for Post Graduate Diploma in Data Science (2020).

## Data Description

The dataset contains information about telecom customers, including their usage patterns, recharge history, and demographic details. The data spans several months. Key variables include:

*   **Usage data:** Call duration (incoming/outgoing, local/STD), data usage (2G/3G).
*   **Recharge data:** Recharge amount, number of recharges, date of last recharge.
*   **ARPU:** Average Revenue Per User.
*   **Demographics:** Age on network (AON).
*   **Service Usage:** Facebook user, Night pack user.
*   For detailed descriptions of each column, refer to the `Data-Dictionary-Telecom-Churn-Case-Study.xlsx` file.

## Technologies Used

*   **Python:**
    *   Pandas
    *   NumPy
    *   Matplotlib
    *   Seaborn
    *   Scikit-learn (sklearn)
    *   Statsmodels
*   **Google Colab:** For exploratory data analysis and model building.

## Setup/Installation

1.  **Clone the repository:**

    ```
    git clone https://github.com/sheetalp97/telecom_churn_analysis
    cd telecom-churn-analysis
    ```

2.  **Open in Google Colab:**

    *   Upload the `Telecom_Churn_Case_Study_Notebook.ipynb` file to your Google Drive.
    *   Open the file with Google Colab (`Open with > Google Colaboratory`).

## Usage

1.  **Obtain the Dataset:**
    *   The complete dataset (`telecom_churn_data.csv`) is available within the `telecom_churn_data.zip` file in this repository.
    *   Download `telecom_churn_data.zip` to your local machine or Google Drive.
    *   Extract the contents of `telecom_churn_data.zip`.
2.  **Open the `Telecom_Churn_Case_Study_Notebook.ipynb` in Google Colab.**
3.  **Run the cells in the notebook sequentially.**  Ensure you have the necessary libraries installed. Colab typically includes most common data science libraries, but you can install any missing ones using `pip install` within a Colab cell (e.g., `!pip install statsmodels`).
4.  **Data Location:** Make sure the notebook can access the `Data-Dictionary-Telecom-Churn-Case-Study.xlsx` file. You might need to upload it to your Google Drive and adjust the file paths in the notebook accordingly.

## Data Dictionary

A detailed data dictionary (`Data-Dictionary-Telecom-Churn-Case-Study.xlsx`) is included in the repository to provide descriptions of each column in the dataset.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.
