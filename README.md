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

The data was collected from a Reddit thread titled ["Plata Thread Vol. 5"](https://www.reddit.com/r/programiranje/comments/13xr2mp/plata_thread_vol_5/) in the r/programiranje subreddit. Comments containing both salary and experience information were manually selected for inclusion in the dataset. To analyze salary distribution across different technologies, a one-hot encoding method was applied. This technique converted categorical variables, such as programming languages or frameworks, into binary vectors. Each technology was assigned a binary value indicating its presence or absence in a data point.










This repository provides a quick analysis of IT salaries in the Balkan region, focusing on data obtained from a Reddit post. The data was processed and visualized using Python, resulting in the creation of scatter plots that reveal interesting trends and correlations between salary levels, professional experience, and various technology skills.

The data was collected from https://www.reddit.com/r/programiranje/comments/13xr2mp/plata_thread_vol_5/
