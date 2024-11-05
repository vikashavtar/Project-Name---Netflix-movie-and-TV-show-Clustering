Netflix Movie and TV Show Clustering
Project Type

Unsupervised Machine Learning
Project Overview

Netflix Inc. is an American media company based in Los Gatos, California. Founded in 1997 by Reed Hastings and Marc Randolph in Scotts Valley, California, it operates the over-the-top subscription video on-demand service Netflix brand, which includes original films and television series commissioned or acquired by the company, and third-party content licensed from other distributors (Wikipedia).

This project aims to analyze a dataset of TV shows and movies available on Netflix. The dataset is collected from Flixable, a third-party Netflix search engine. The goal is to group the content into relevant clusters using NLP techniques to improve the user experience through a recommendation system. This analysis will help prevent subscriber churn for Netflix, which currently has over 220 million subscribers.

Additionally, the dataset will be analyzed to uncover insights and trends in the streaming entertainment industry.
Project Summary

The project followed a step-by-step process:

    Handling Null Values: Addressing any missing data within the dataset to ensure completeness and accuracy.

    Managing Nested Columns: Breaking down complex columns (such as director, cast, listed_in, country) for better visualization and analysis.

    Binning the Rating Attribute: Categorizing the rating attribute into meaningful groups (adult, children's, family-friendly, not rated).

    Exploratory Data Analysis (EDA): Conducting a thorough analysis to gain insights for preventing subscriber churn.

    Clustering:
        Attributes Used: Director, cast, country, genre, rating, and description.
        Techniques: Tokenizing, preprocessing, and vectorizing the attributes using TF-IDF vectorizer.
        Dimensionality Reduction: Using PCA to reduce the dataset's dimensions and improve performance.

    Clustering Algorithms:
        K-Means Clustering: Determining the optimal number of clusters to be 4.
        Agglomerative Hierarchical Clustering: Determining the optimal number of clusters to be 2.

    Content-Based Recommender System: Developing a system using a cosine similarity matrix to provide personalized recommendations to users, thereby reducing subscriber churn for Netflix.

Project Goals

    To enhance user satisfaction and retention rates for Netflix by providing a personalized viewing experience.
    To uncover insights and trends in the streaming entertainment industry through comprehensive data analysis.

Dataset

The dataset consists of TV shows and movies available on Netflix until 2019, sourced from Flixable.
Steps Followed

    Data Preprocessing: Handling null values and managing nested columns.
    Rating Binning: Categorizing the rating attribute.
    EDA: Gaining insights from the data.
    NLP Techniques: Tokenizing, preprocessing, and vectorizing attributes.
    Dimensionality Reduction: Using PCA.
    Clustering: Applying K-Means and Agglomerative Hierarchical Clustering algorithms.
    Recommender System: Developing a content-based recommendation system.

Expected Outcomes

    Enhanced user experience on Netflix through personalized recommendations.
    Improved retention rates by preventing subscriber churn.
    Valuable insights into the streaming entertainment industry.

By following this comprehensive analysis and clustering process, Netflix can improve its recommendation system, leading to greater user satisfaction and retention.
