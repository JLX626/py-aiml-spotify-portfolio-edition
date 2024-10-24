# Course-End Project: Rolling Stones Spotify Data Analysis

## Overview
This project is the culmination of the Machine Learning course in the AI and Machine Learning Bootcamp offered by Caltech Center for Technology and Management Education (CTME). It focuses on applying machine learning techniques, specifically clustering analysis, to the Rolling Stones' discography using Spotify data. The goal is to identify patterns in the audio features and popularity of the band's tracks, demonstrating the application of machine learning in music data analysis.

As outlined in the course-end project problem statement, our main objectives are to perform exploratory data analysis on the Rolling Stones' Spotify data, conduct cluster analysis to create cohorts of songs, understand the various factors that contribute to these cohorts, and provide insights on how Spotify might categorize and recommend Rolling Stones tracks.

## Project Structure
```
py-aiml-stones/
│
├── data/
│   ├── raw/
│   │   ├── spotify_rolling_stones.csv
│   │   └── spotify_features_dictionary.xlsx
│   └── processed/
│       ├── full_tracks.csv
│       ├── clustering_tracks.csv
│       ├── outliers.csv
│       ├── flagged_tracks.csv
│       └── stones_tracks_enriched.csv
│
├── notebooks/
│   ├── helper_functions.ipynb
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_and_feature_engineering.ipynb
│   └── 03_clustering_analysis.ipynb
│
├── requirements.txt
└── README.md
```

## Project Components

### Data Directory
- **raw/**: Contains the original Spotify data files.
- **processed/**: Contains cleaned and preprocessed data files.

### Notebooks Directory
- **helper_functions.ipynb**: Contains utility functions used across other notebooks.
- **01_data_cleaning.ipynb**: Data loading, cleaning, and preprocessing.
- **02_eda_and_feature_engineering.ipynb**: Exploratory Data Analysis (EDA) and feature engineering.
- **03_clustering_analysis.ipynb**: K-means clustering analysis and interpretation of results.

## Project Execution Flow

1. **Data Cleaning:** Use `01_data_cleaning.ipynb` to load, inspect, and clean the raw data.
2. **EDA and Feature Engineering:** Use `02_eda_and_feature_engineering.ipynb` to perform statistical analysis and create new features.
3. **Clustering Analysis:** Use `03_clustering_analysis.ipynb` to perform clustering and interpret results.

Note: Helper functions are run at the beginning of each notebook using `%run "./helper_functions.ipynb"`.

## Technologies Used

- **Python**: Primary programming language
- **Jupyter Notebooks**: For interactive development and documentation
- **pandas & numpy**: Data manipulation and analysis
- **matplotlib & seaborn**: Data visualization
- **scikit-learn**: For machine learning operations (clustering)
- **Git**: Version control
- **Custom visualization styling**: Created a Rolling Stones-inspired color palette and plot style for consistent, themed data visualization

## Key Machine Learning Applications

- **Feature Engineering**: Created custom features "groovy factor" and "raw energy"
- **Dimensionality Reduction**: Applied Principal Component Analysis (PCA) for feature selection
- **Clustering**: Implemented K-means clustering to identify distinct groups of songs
- **Model Evaluation**: Used silhouette analysis and elbow method to determine optimal number of clusters

## Key Insights and Recommendations

The project provided several key insights through machine learning analysis:
- Identified three distinct clusters of songs: Energetic Crowd-Pleasers, Groovy Hits, and Raw Classics
- Observed trends in the band's sound over time, with more recent tracks leaning towards the "Groovy Hits" cluster
- Recognized the importance of danceability and energy in determining a track's popularity on Spotify
- Discovered the significance of thorough data cleaning and the potential impact of data quality issues on analysis results

These insights demonstrate how machine learning can be applied to music data to uncover patterns and trends that could inform business decisions in the music industry.

## Conclusion

This project not only demonstrates the application of machine learning techniques to analyze and derive insights from music streaming data, but also highlights the iterative and often non-linear nature of real-world data science projects. It showcases skills in data preprocessing, exploratory data analysis, feature engineering, and clustering analysis, all key components of the Machine Learning course. Moreover, it provides valuable lessons in data quality management, critical thinking, and the importance of continuous learning and adaptation in the field of data science.

## About the Author

Jason Lampitt is an innovative digital product leader with over 25 years of experience across high-profile industries. He is currently expanding and amplifying his expertise by focusing on the strategic integration of AI, Machine Learning, and Data Science into user-centric solutions. Jason's approach ensures responsible development of emerging technologies, leveraging his extensive background in digital transformation to address complex challenges in the AI landscape.

[Connect with Jason on LinkedIn](https://www.linkedin.com/in/jlampitt/)

## Statement of Original Work

This project represents my individual effort and original work as the course-end project for the Machine Learning course in the Caltech CTME AI and Machine Learning Bootcamp. All data analysis, visualizations, and machine learning implementations presented here are the result of my own work, leveraging the knowledge and skills gained throughout the bootcamp.

While I have utilized standard libraries and followed best practices taught in the course, the specific implementation, analytical decisions, and insights drawn are my own. This work reflects my current understanding and application of machine learning principles and practices.

This project was developed under the guidance of the [Caltech Center for Technology and Management Education (CTME)](https://ctme.caltech.edu/).

Thank you for reviewing my work.

## Acknowledgements

Data sourced from Spotify's API. This project is for educational purposes only and is not affiliated with the Rolling Stones or Spotify.