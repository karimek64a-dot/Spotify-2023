Spotify 2023 Data Analysis | Power BI
Project Overview

This project explores Spotify's 2023 music dataset using Power BI to analyze streaming performance, artist popularity, track characteristics, and music release trends.

The goal was to transform raw music data into an interactive, visually engaging dashboard that provides a clearer understanding of music trends and streaming performance.

The project includes three analytical pages, each focusing on a different aspect of Spotify's music data, with a consistent dark-green theme inspired by Spotify's visual identity.

Dashboard Preview
1. Spotify Hits & Performance

This page provides an overview of streaming performance, track popularity, artist performance, and release trends.

2. Spotify Music DNA

This page explores the musical characteristics of tracks, including energy, danceability, BPM, and other audio features.

3. Spotify Release Strategy

This page focuses on release-year trends and streaming patterns to explore how music releases vary over time.

Data Source

The project uses the Spotify 2023 dataset, which contains information about tracks, artists, streaming counts, release dates, and audio characteristics.

The dataset includes fields such as:

Track names and artist names
Release year, month, and day
Total streams
BPM
Danceability
Energy
Valence
Speechiness
Acousticness
Instrumentalness
Liveness
Tools & Technologies
Power BI Desktop: Dashboard development and interactive visualization.
Power Query: Data cleaning and transformation.
DAX: Measures and analytical calculations.
Data Modeling: Date dimension creation and data organization.
CSV: Source data format.
Project Workflow
1. Data Import & Understanding
Imported the Spotify dataset into Power BI.
Reviewed the dataset structure and column types.
Identified the fields required for streaming, artist, and music-characteristic analysis.
2. Data Cleaning & Transformation

Using Power Query, I prepared the dataset for analysis by reviewing data types, organizing the relevant columns, and preparing release-date information for time-based analysis.

The transformation process helped structure the data for use in the dashboard.

3. Data Modeling
Created a dedicated Date Dimension (Dim Date).
Used release-date information to support time-based analysis.
Added a Date ID to help organize date-related data.
Prepared the model for analyzing tracks across release dates and years.
4. DAX Measures

Created DAX measures to support the dashboard's analytical requirements, including:

Total Tracks
Total Streams
Total Artists
Average Streams per Artist
Best Performing Artist
Total Streams by Release Year

These measures support the dashboard's KPIs and visual comparisons.

5. Dashboard Development

Designed an interactive, three-page Power BI report with a dark-green theme and Spotify-inspired styling.

The dashboard combines KPI cards, tables, bar charts, a donut chart, a scatter plot, and time-based visualizations to make the data easier to explore.

Key Analytical Areas
Streaming performance and track rankings
Artist performance and contribution to streams
Music characteristics and audio-feature comparisons
Release-year trends
Relationships between danceability and energy
Comparisons of track performance across different categories
Key Learnings

This project helped me strengthen my practical understanding of:

Data cleaning and transformation with Power Query
Data modeling and date dimensions
DAX measures and analytical calculations
Interactive dashboard development
Data visualization and analytical storytelling

It also reinforced the importance of preparing and organizing data before building meaningful visualizations.

Project Files

The repository includes the Power BI report, DAX documentation, Power Query step documentation, and dashboard screenshots.

Explore the complete project:

Spotify 2023 Data Analysis — GitHub Repository

Author

Karim Tarek
Aspiring Data Analyst | Power BI | Excel | SQL | Python

LinkedIn: Karim Tarek
Portfolio: View My Portfolio

This project represents a practical step in my data analytics journey, combining data preparation, modeling, DAX, and interactive visualization to turn raw data into meaningful insights.
