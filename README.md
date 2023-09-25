# Global YouTube Statistics Readme 



This project conducts a thorough global analysis of YouTube channel statistics, aiming to reveal insights into rankings, subscribers, video views, earnings, and more. It goes beyond surface-level observations, striving to uncover trends and patterns in the platform's dynamics. By exploring diverse aspects of YouTube, it provides valuable context and narratives behind the data. Ultimately, this analysis empowers stakeholders and content creators with actionable insights for strategic decision-making.

## Data Source

The project uses a dataset titled "Global YouTube Statistics.csv" for analysis. This dataset contains extensive information about various YouTube channels, including their rankings, subscribers, video views, categories, countries, and more.

## Data Preprocessing

### Cleaning Missing Data

Before analysis, data quality is ensured by cleaning missing values. The "nan" values are replaced with Pandas' `NA`, and relevant columns are converted to numeric data types. Any rows with missing data are removed from the dataset.

## Visualizations

### Top 10 YouTube Channels by Subscribers

The analysis begins by identifying and visualizing the top 10 YouTube channels with the most subscribers. The resulting bar chart provides a quick overview of these high-subscriber channels.

### YouTube Channels: Subscribers, Video Views, and Uploads

In this section, a 3D scatter plot showcases the relationship between subscribers, video views, and uploads across YouTube channels. The plot offers a multidimensional perspective on channel statistics.

### Subscribers vs. Video Views by Category

This part of the analysis explores the relationship between subscribers and video views while categorizing channels by their content type. The result is a scatter plot with size and color encoding that highlights various channel categories.

### Distribution of YouTube Channel Types

A Sunburst chart is employed to visualize the distribution of different YouTube channel types. This chart provides insights into the variety of content available on the platform.

### Distribution of Earnings

The final section of the analysis presents box plots to illustrate the distribution of earnings among YouTube channels. These plots give an overview of the earnings range within the dataset.

## Conclusion

This repository provides a comprehensive analysis of global YouTube statistics. It serves as a valuable resource for gaining insights into channel rankings, subscribers, video views, earnings, and more. The visualizations and findings presented here can be used as a foundation for further exploration and analysis of YouTube data.
