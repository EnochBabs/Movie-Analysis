# Netflix Data Analysis and Visualization

## Overview
This project involves the analysis and visualization of a Netflix dataset containing information about movies and TV shows available on the platform. The dataset includes details such as titles, directors, cast, countries, release years, ratings, genres, and more. The project uses Python libraries like Pandas, NumPy, Seaborn, Matplotlib, and Folium for data manipulation, visualization, and geographical representation.

## Features
1. Data Loading and Exploration
Load the Netflix dataset using Pandas.
Display the first few rows of the dataset (head()).
Inspect the structure, data types, and missing values in the dataset (info(), isnull().sum()).

2. Missing Data Visualization
Visualize missing data using a heatmap (sns.heatmap).

3. Content Types Analysis
Count and visualize the distribution of content types (Movies vs. TV Shows) using a bar chart and a pie chart (sns.countplot, plt.pie).

4. Top Directors
Identify and visualize the top 10 directors with the most films (value_counts(), sns.barplot).

5. Content Production by Country
Identify the top 10 countries producing content.
Visualize the data using a bar chart (sns.barplot).

6. Geographical Visualization
Use Folium to create a map showing the top content-producing countries.
Customize markers with country-specific information (count of titles).

7. Release Trends
Analyze and visualize the number of TV series and movies released each year using line plots (sns.lineplot).

8. Content Added to Netflix
Extract the year and month when content was added to Netflix.
Visualize the trends of content addition over time using bar charts (sns.barplot).

9. Category Analysis
Extract and count categories from the listed_in column.
Visualize the top 10 most listed categories using a bar chart (sns.barplot).

10. Horror Movies and Thrillers
Analyze the release years of horror movies and thrillers.
Visualize the top 10 years for horror movie releases using a pie chart (plt.pie).

11. Top Cast Members
Extract and count the most frequent cast members in the dataset.
List the top 10 cast members with the highest appearances.
Installation
To run the project, install the required libraries:

## Dataset Columns
show_id: Unique identifier for each title.

type: Movie or TV Show.

title: Title of the content.

director: Director of the content.

cast: Cast members.

country: Country of production.

date_added: Date content was added to Netflix.

release_year: Year of release.

rating: Content rating (e.g., PG-13, TV-MA).

duration: Duration of the content.

listed_in: Categories/genres of the content.

description: Brief description of the content.
