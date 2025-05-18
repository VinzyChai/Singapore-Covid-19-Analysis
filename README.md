# Project's Title
Singapore-Covid-19-Analysis

# Description
In late December 2019, COVID-19 emerged and has since claimed over 5 million lives worldwide. Researcher May conducted an analysis to understand the pandemic by the numbers and examine its impact on the delivery of health services.

# Import Dictionaries
For numerical computing and data manipulation
```py
import numpy as np
import pandas as pd
```
For working with date and time
```py
import datetime
```
For using Bokeh function to plot
```py
import pandas_bokeh
from bokeh.plotting import figure, output_file, show
from bokeh.models import Label, HoverTool, ColumnDataSource, FactorRange, Panel, Tabs,
from bokeh.transform import factor_cmap
from bokeh.palettes import Turbo256, Viridis256
```
For basic plotting and statistical visualization
```py
import matplotlib.pyplot as plt
import seaborn as sns
```
For plotting interactive SVG charts
```py
import pygal
```

# Run the code (Google Colab)
Go to runtime and hit 'run all'

# Dataset 
1. Covid-19 case numbers
2. Covid-19 hospital admissions
3. Covid-19 vaccination
4. Coronavirus (COVID-19) Deaths

I obtained the dataset from the Data.gov.sg website. All the data is in English and presented in Excel format. 

# Usage
Run the code to explore various types of plots, each offering a unique insight into the dataset. For example, the line graph illustrates the epidemic curve over time, while the bar charts show ICU bed utilization and ICU admissions. The boxplot compares average deaths of active ICU cases per 100k population based on vaccination status. The scatterplot reveals the relationship between fatality rate and vaccinated population, and the solid gauge chart visualizes vaccination coverage by age group for both full regime and at least one dose.

*The attached PowerPoint provides a detailed explanation of the entire research. Please refer to it for more information.*
