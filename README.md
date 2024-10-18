# Automated Mpox Heatmap Creation
**Overview**

This repository contains two Jupyter notebooks that analyze targeted sites using heat map visualizations. The project aims to provide insights into geographic distributions and patterns in the data.

**Background**
With the PALM 007 trial emphasizing time to lesion resolution as a key metric for assessing Tecovirimat's effectiveness, the need for accurate and accessible data visualization is essential. This is where the automated heatmap project comes into play, and it has two main objectives. The first objective is to automate the visualization of active lesion distribution over time using heat maps. This enables a straightforward representation of treatment progress, directly linked to the trial's primary endpoint. The second objective is to compare AI-detected counts with raw lesion counts, ensuring accuracy and reliability in data analysis.

**BaselineHeatMap_240405.ipynb**:
This notebook establishes a baseline heat map of the initial dataset. It includes steps for data loading, preprocessing, and generating a heat map that visualizes the geographic distribution of sites.
Key components: Data import and cleaning, Baseline heat map generation, and Visualization of site density

**TargetedSitesHeatMap_240416.ipynb**:
This notebook focuses on targeted sites based on specific criteria. It builds upon the baseline analysis to highlight the targeted sites on a heat map.
Key components: Filtering data to identify targeted sites, Creating an enhanced heat map with targeted overlays, and Comparison with baseline results to show improvements or changes
