# Visualizations-Activity

Data Visualization: Histogram and Scatter Plot

This repository contains two visualizations created using the dataset "bad-drivers.csv" from FiveThirtyEight. The visualizations include a histogram and a scatter plot. Below is a brief description of each visualization:

Histogram
The histogram visualizes the distribution of the "Number of drivers involved in fatal collisions per billion miles" variable. It provides insights into the frequency of fatal collisions across different ranges or bins. The x-axis represents the value ranges, while the y-axis represents the frequency or count of occurrences. The histogram helps identify any significant peaks, clusters, or patterns in the distribution of fatal collisions per billion miles.

Scatter Plot
The scatter plot visualizes the relationship between two variables: the percentage of drivers involved in fatal collisions who were speeding and the percentage of drivers involved in fatal collisions who were alcohol-impaired. Each point in the scatter plot represents a state in the dataset. The x-axis represents the percentage of drivers involved in fatal collisions who were speeding, while the y-axis represents the percentage of drivers involved in fatal collisions who were alcohol-impaired. The scatter plot helps identify any patterns or correlations between these two variables.

Repository Contents
data/bad-drivers.csv: The dataset used for creating the visualizations.
histogram.R: R script to generate the histogram visualization.
scatterplot.R: R script to generate the scatter plot visualization.
README.md: This README file providing an overview of the visualizations.
Requirements
To run the R scripts and generate the visualizations, the following packages need to be installed:

readr
ggplot2
You can install these packages using the following commands:

R
Copy code
install.packages("readr")
install.packages("ggplot2")
Usage
To replicate the visualizations, follow these steps:

Download the dataset, "bad-drivers.csv," and save it in the data directory.
Run the histogram.R script to generate the histogram visualization.
Run the scatterplot.R script to generate the scatter plot visualization.
The visualizations will be displayed or saved as image files, depending on the scripts.
Feel free to modify the scripts or explore other variables in the dataset to create different visualizations.
