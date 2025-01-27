# Monsoon-Analysis

This script analyzes and visualizes monsoon rainfall in Pakistan using the CHIRPS Daily Precipitation dataset for the years 2010 to 2024. It focuses on the monsoon season (June to September) by summing the daily precipitation during these months for each year. The boundary of Pakistan is defined using the USDOS LSIB SIMPLE 2017 dataset, and the rainfall data is clipped to this region to provide insights specific to the country's geographical boundary.

The code utilizes the getMonsoonRainfall() function to filter and sum precipitation data for each year within the specified monsoon months. This function applies a visualization scheme using a color palette ranging from white (low rainfall) to purple (high rainfall), allowing users to visually interpret the spatial distribution of rainfall across Pakistan. Layers for each year's monsoon rainfall are dynamically added to the map for comparison and analysis.

Additionally, a legend panel is included to enhance the interpretability of the rainfall map. The legend displays the color bar corresponding to rainfall intensity (0 to 800 mm), along with clearly labeled minimum and maximum values. The map is centered on Pakistan for an intuitive view, making it an effective tool for understanding the temporal and spatial variability of monsoon rainfall in Pakistan over the specified period.
