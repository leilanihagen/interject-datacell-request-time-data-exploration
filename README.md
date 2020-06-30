# Interject Datacell Request Time Data Exploration

## Purpose

The purpose of this project was to use Jupyter Notebooks to explore and visualize data that had been collected at Interject over the years, pertaining to the durations of time taken for certain Interject reporting functions to execute. This data was collected on a per-client basis.

The Notebook is intended to be used both by developers at Interject, to find possible bugs or performance tie-ups, and by clients, to gain insight into better ways of using reporting functions in their projects to optimize performance.

## Implementation

The Notebook was developed to give the user the ability to plug in their own data with minimal effort or knowledge of code/Python. To accomplish this, I created various functions that allow the user to give connection details, and specify parameters for which data (between certain dates, etc.) to use for the visualizations.

Pandas was used to hold and filter data after importing the original data from SQL Server databases. Matplotlib and Seaborn were employed to create, different visualizations of the data.

## About Interject

Interject is a data-solutions company that focuses on improving the productivity of their clients' businesses in the areas of reporting and accounting, data management, and other custom solutions. I worked as a member of the Interject student team from May 2019 until February 2020. Check out Interject's website at: gointerject.com.

This project was developed solely by me.
