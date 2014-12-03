# Visualizing Worldwide Agricultural Data in Python

## Intent
This repo integrates some public data from the Food and Agriculture Organization of the United Nations (FAO) with Python data analysis and plotting tools, namely, Pandas and Matplotlib.

My goal was to create an animated scatter plot using worldwide data and to also generalize it for other datasets (education, socioeconomic metrics, etc.)

## Reusable code
The code in notebook.ipynb under the ```Animated "heatmap" using z-score of average country yield per year 
- Pure Matplotlib/Basemap``` heading is essentially data-independent, except for titles/axis labels. The input 
format is a Pandas dataframe of z-scores, with columns being years and row indices being country names, meaning 
the value at each element is a z-score for a given country, in a given year.
