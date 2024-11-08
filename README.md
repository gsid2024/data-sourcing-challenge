# data-sourcing-challenge
mod 6
Overview
This project aims to prepare a dataset for predicting Geomagnetic Storms (GSTs) based on Coronal Mass Ejections (CMEs). The data is retrieved from NASA's API and processed to facilitate analysis and machine learning modeling.

Files Included
retrieve_data.ipynb: Jupyter Notebook containing the code for data retrieval, processing, and analysis.
cme_gst_data.csv: The final exported CSV file containing the cleaned dataset.
Data Sources
NASA's DONKI API: The data for CMEs and GSTs is sourced from NASA's Daily Optical and Near-Infrared Observations (DONKI) API.
Key Steps
Data Retrieval:

Retrieved CME and GST data using API calls.
Data Processing:

Cleaned and filtered data to keep relevant columns.
Handled missing values and exploded nested lists into separate rows.
Merged the CME and GST datasets based on their respective activity IDs.
Data Analysis:

Computed time differences between CME and GST occurrences.
Calculated mean and median time differences to understand the relationship.
Export:

Exported the final merged dataset to a CSV file for further use.
