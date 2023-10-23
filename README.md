# Geospatial Analysis of Yelp User Behavior
This project aims to analyze Yelp user behavior based on geospatial locations, combining sentiment and geospatial analysis techniques. It identifies patterns and trends in user behavior across different locations through spatial segmentation and visualizations such as heat maps, scatter plots, and choropleth maps.

## Table of Contents
1. Introduction
2. Setup and Dependencies
3. Data Collection
4. Data Cleaning and Preprocessing
5. Geospatial Analysis
6. Evaluation and Results
7. Visualizations
8. Conclusion and Future Work

## Introduction

This project focuses on:

1. Integrating Yelp data with geospatial analysis techniques to derive insights into Yelp user behavior across different geospatial locations.

2. Combining sentiment analysis and geospatial analysis for location-based insights and trends related to review sentiments.

3. Applying cluster analysis for spatial segmentation to identify patterns and trends in Yelp user behavior across different geospatial segments.

4. Incorporating visualizations for data analysis, such as heat maps, scatter plots, and choropleth maps.

## Setup and Dependencies

First, download the original data from the [Yelp Open Dataset](https://www.yelp.com/dataset) since it is too large to upload to GitHub. The dataset is in JSON format, but you can convert it to CSV using [Yelp's example code](https://github.com/Yelp/dataset-examples). To run our analysis, you only need the yelp_academic_dataset_review.csv file after conversion. Our provided file, YelpChallengeWMetros_Clean.csv, is a cleaned version of yelp_academic_dataset_business.csv obtained by downloading the dataset and using the converter. Or you can just use our processed dataset - Here is a processed dataset that we have prepared: [Data](https://www.dropbox.com/sh/8m7atj7b2zp0iv2/AABucyarf-LHhJZ6JEb8vFQOa?dl=0)

To set up and run this project, you need to have Python 3.x installed and the following Python libraries:

- Pandas
- Numpy
- Geopandas
- Shapely
- Scikit-learn
- NLTK or spaCy
- Matplotlib
- Seaborn
- Folium

You can install the dependencies using the following command:

```pip install pandas numpy geopandas shapely scikit-learn nltk spacy matplotlib seaborn folium```

## Execution

1. Collect Yelp user data: reviews, ratings, etc., by running the data_collection.ipynb notebook.
2. Clean and preprocess the data using the data_cleaning_and_preprocessing.ipynb notebook by Mengyuan.
3. Identify important keywords from Yelp reviews using the keyword_identification.ipynb notebook by Siying.
4. Aggregate keywords based on geospatial locations with the location_based_keyword_aggregation.ipynb notebook by Siying.
5. Visualize geospatial analysis results using the visualizations.ipynb notebook by Hao Hu.
Analyze regional trends in Yelp user behavior with the regional_trend_analysis.ipynb notebook by Yaxin.
6. Apply spatial clustering techniques using the spatial_clustering.ipynb notebook by Xianyi.

## Demo
Here is the URL to a [demo video on YouTube](https://youtu.be/cZWj-torlqY)

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments
- Thanks to Yelp for providing the data through the Yelp API and Yelp Dataset Challenge.
- Special thanks to the open-source community for providing useful libraries and tools used in this project.
