# COVID-19 Tracker

This is a simple script that downloads a table of the total number of COVID-19 cases and deaths reported each day by the WHO and plots the progression of the disease in each country.

## Requirements

The code is a jupyter notebook and depends on pandas and Plotly Express.

## How to use it

The script plots the number of cases vs. the number of days since the country's total cases exceeded a user-specified threshold (e.g. days since there were 50 cases, or days since there were 200 cases).