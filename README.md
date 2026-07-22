# Spacewalks

## Overview

Spacewalks is a python analysis tool for researchers to develop visulatizations and statistical summaries of NASA's extravehicular activity datasets.

## Features
Key features of Spacewalks:

- Generates a CSV table of summary statistics of extravahicular activity crew sizes.
- Generates a line plot so show the cumulative duration of space walks over time.

## Pre-requisites

Spacewalks was developed using Python version 3.12

To install and run Spacewalks you will need have Python >=3.12
installed. You will also need the following libraries (minimum versions in brackets)

- [NumPy](https://www.numpy.org/) >=2.0.0 - Spacewalk's test suite uses NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) >=3.0.0  - Spacewalks uses Matplotlib to make plots
- [pytest](https://docs.pytest.org/en/8.2.x/#) >=8.2.0  - Spacewalks uses pytest for testing
- [pandas](https://pandas.pydata.org/) >= 2.2.0 - Spacewalks uses pandas for data frame manipulation 

## Installation Instructions
To install execute the following commands in terminal. These clone the spacewalks repository to your local machine using git and install the necessary depndencies. 

```
git clone git@github.com:mjzenz/spacewalks.git
cd spacewalks
python -m pip install -r requirements.txt
```


## Usage Example
To run the analysis using the built in data, run the script using Python.
```
python eva_data_analysis.py eva-data.json eva-data.csv
```

The first argument is the path to the json data file and the second is the path to the csv output file.