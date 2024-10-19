# Spotify Tracks Exploratory Data Analysis

## Introduction
The "Spotify Tracks Analysis" project involves the exploration and visualization of a dataset containing information about various Spotify tracks. The primary goal is to gain insights into the characteristics of the songs, identify patterns, and understand how certain features correlate with each other. The analysis is conducted using Python programming language and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Data Loading and Cleaning
The project begins with loading the dataset using the Pandas library. The dataset, stored in a CSV file, includes information about each track, such as its ID, name, popularity, duration, artists, release date, and various musical features. To ensure data quality, initial checks are performed to identify missing values using the `pd.isnull()` and `info()` functions.

## Exploratory Data Analysis
### 1. 10 Least Popular Songs
The analysis starts by identifying and displaying the 10 least popular songs in the dataset. Songs are sorted based on their popularity in ascending order, and the relevant information is presented.

### 2. 10 Popular Songs with Popularity > 90
Another exploration focuses on showcasing the 10 most popular songs with a popularity score greater than 90. This information is filtered and sorted accordingly.

## Data Transformation
To facilitate further analysis, the project includes data transformation steps. The duration of the songs, initially provided in milliseconds, is converted to seconds for better interpretation. The "duration_ms" column is dropped, and a new "duration" column is created.

## Visualization
### Correlation Heatmap
A correlation heatmap is generated to visualize the relationships between numerical variables in the dataset. The heatmap provides insights into how different features correlate with each other. Certain columns, such as "key," "mode," and "explicit," are dropped before calculating the correlation.
![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/7fcca6ad-ce75-45f9-b4e5-88c93a3d49d6)


### Regression Plots
Two regression plots are created to explore relationships between specific pairs of variables. The first plot examines the correlation between loudness and energy, while the second analyzes the relationship between popularity and acousticness. These visualizations help in understanding the trends and patterns within the data
![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/d6891b87-166a-4dce-a2bc-6497e74ca0b2)

![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/e67c8b84-1ee2-43d3-9b43-39d6300db6a7)

### Duration of Songs Over the Years
The project includes bar and line plots to analyze the average duration of songs over the years. The visualizations provide a historical perspective on how the duration of songs has evolved.
![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/f52731f2-fe76-48d5-bbe5-2df0f44f0dfe)

![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/c1afae7e-0944-4a28-ba0c-d9ce496bcc81)

## Conclusion
The "Spotify Tracks Analysis" project offers a comprehensive exploration of the dataset, uncovering patterns, correlations, and trends in Spotify tracks. Through descriptive statistics and visualizations, the project provides valuable insights into the characteristics of songs, allowing for a better understanding of the musical landscape captured in the dataset.
