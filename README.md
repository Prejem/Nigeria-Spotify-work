Objective of the Analysis
The main aim of this analysis is to understand the patterns and characteristics of Nigerian songs on Spotify using the dataset provided. In this project, popularity is used as a measure of how well a song performs.

The analysis focuses on:

Studying how song popularity changes over time

Comparing the performance of different music genres

Examining the distribution of audio features like danceability, energy, and tempo

Identifying any unusual values (outliers) in the dataset

Understanding which features influence song popularity the most

Steps Followed
To carry out this analysis, the following steps were taken:

First, the dataset was loaded into Python using pandas.

Next, some basic data cleaning was done. This included checking for missing values and making sure all columns had the correct data types. After that, only the numerical columns were selected for further analysis.

Then, different visualizations were created to explore the data. A line plot was used to show how popularity changes over time, while a bar chart was used to compare total popularity across different genres. Box plots were also created for all numerical columns to understand their distribution and detect outliers.

Finally, a machine learning model (Random Forest) was built, and SHAP was used to explain how different features affect the prediction of song popularity.


Key Observations from the Plots
From the line plot, it can be seen that song popularity changes over the years. In general, there may be an increasing trend, which could mean that Nigerian music is gaining more attention globally. However, there are also some fluctuations, showing that not every year has the same level of success.

The bar chart shows that some genres have higher total popularity than others. This suggests that certain genres are more popular among listeners, while others are less common or have a smaller audience.

From the box plots, it is clear that different features have different distributions. Some features have a small spread, meaning most songs have similar values, while others have a larger spread, showing more variation. There are also some outliers in the data, which represent songs with extreme values compared to the rest.

The SHAP analysis shows that some features, such as energy and danceability, have a strong influence on popularity. This means that songs with higher values in these features are more likely to be popular. Other features may have less impact or even reduce popularity depending on their values.
