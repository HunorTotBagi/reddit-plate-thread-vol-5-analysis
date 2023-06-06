# Reddit Salaries Thread Vol 5 - Analysis

This repository contains code for analyzing and visualizing data from a CSV file using the Python libraries matplotlib, seaborn, and pandas. The code generates PDF reports with various plots and histograms.

## Prerequisites

Before running the code, ensure that you have the following dependencies installed: 
- `matplotlib`
- `seaborn`
- `pandas`
- `numpy`

You can install these libraries using `pip`:
```
pip install matplotlib seaborn pandas numpy

```

## Data

The data was collected from a Reddit thread titled ["Plata Thread Vol. 5"](https://www.reddit.com/r/programiranje/comments/13xr2mp/plata_thread_vol_5/) in the r/programiranje subreddit. Comments containing both salary and experience information were manually selected for inclusion in the dataset. 

To analyze salary distribution across different technologies, a one-hot encoding method was applied. This technique converted categorical variables, such as programming languages or frameworks, into binary vectors. Each technology was assigned a binary value indicating its presence or absence in a data point.

## Code Explanation

- The code performs the following tasks:

- Reads the data from the data.csv file into a pandas DataFrame.

- Drops columns from the DataFrame that have only one unique value.

- Defines a function ploting that generates scatter plots for specific subsets of data.

- Calculates the frequency of occurrence for each column in the DataFrame and stores it in a dictionary.

- Sorts the dictionary based on the frequency in descending order.

- Generates scatter plots for each subset of data using the ploting function and saves them in the generated_images.pdf file.

- Generates histograms for the 'Salary' column and saves them in the salary_histograms.pdf file.

## Outputs
### generated_images.pdf
This PDF file contains scatter plots for subsets of data based on the columns in the DataFrame. Each plot represents the relationship between 'Experience' (x-axis) and 'Salary' (y-axis) for a specific subset.

### salary_histograms.pdf
This PDF file contains two histograms of the 'Salary' column. The first histogram shows the distribution in salary range 0 to 10000, the second from range from 0 to 4500 

