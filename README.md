# Nairobi Air Quality Analysis

<p float="left"> <img src="Air Quality in Nairobi1.png" width="30%" /> <img src="Air Quality in Nairobi2.png" width="30%" /> <img src="Air Quality in Nairobi3.png" width="30%" /> </p>


### Introduction
This project analyzes air quality in Nairobi using environmental monitoring data. The goal is to explore whether pollution levels are influenced more by location or time patterns. The analysis includes data cleaning, feature extraction, and visualization techniques such as histograms, boxplots, time-series plots, and correlation analysis. Insights are drawn for spatial differences, with a special focus on high-pollution areas.

And this is what I did: cleaned the data, created new features for latitude, longitude, and monitoring area, transformed pollution values to numeric format, explored the data through summary statistics and visualizations, and calculated correlations to understand the relationship between pollutant concentration and time across different locations :

*Import libraries*

```python
import pandas as pd
import matplotlib.pyplot as plt
import plotly.express as px
```

## Conclusion
The analysis shows that air pollution levels in Nairobi are influenced by both location and temporal patterns. Some areas consistently experience higher pollution concentrations, while fluctuations over time reveal changing environmental conditions. Through data cleaning, visualization, and correlation analysis, clear patterns emerged showing how pollution varies across locations and time periods. Overall, the project demonstrates how data analysis can uncover meaningful environmental trends and support evidence-based insights into urban air quality.
