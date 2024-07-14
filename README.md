# TMDB Movie Data Analysis (930K Movies)

**Course:** CSC17104 - Programming for Data Science

**Group 25**

| Student ID | Name                  | Completion (%) |
|------------|----------------------|----------------|
| 21120178   | Van Ba Bao Huy         | 100%          |
| 21120071   | Nguyen Thi Thanh Hoa   | 100%          |
| 21120174   | Nguyen Thi Gai        | 100%          |

## Introduction

This project analyzes the TMDB Movies Dataset 2023, containing information on over 930,000 movies. The goal is to explore, preprocess the data, and ask meaningful questions to gain deeper insights into the film industry.

## Data Source

* **Topic:** Detailed movie information (title, ratings, revenue, genre, etc.)
* **Source:** Kaggle ([https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data))
* **License:** CC0: Public Domain (no copyright)

## Research Questions

1.  **What are the characteristics of a high-grossing film?**
    * Significance: Identify factors influencing movie revenue to optimize production strategies.

2.  **Which movie genres have been the most popular over the years from 2000 to 2023?**
    * Significance: Recognize changing audience preferences to adjust production and marketing.

3.  **Which 10 countries have the highest total number of films on TMDB each year?**
    * Significance: Assess the global film market, Vietnam's position, and forecast trends.

4.  **What genres do the 5 highest-grossing companies focus on producing?**
    * Significance: Understand audience preferences, inform strategic production decisions, and diversify products.

5.  **For each movie a user searches for or has watched, what other movies with similar content/genre should we recommend?**
    * Significance: Enhance user experience, increase engagement and revenue for film distribution platforms.

## Methodology & Results

* **Preprocessing:** Remove duplicate data, handle missing values, convert data types.
* **Analysis:** Utilize statistical techniques, visualizations (charts, word clouds), and correlation analysis.
* **Movie Recommendations:** Apply Demographic Filtering (based on ratings) and Content Based Filtering (based on content).
* **Detailed Results:** See the attached Jupyter Notebook file.

## Discussion & Future Directions

* **Limitations:** Some data columns are unused, missing values and noise need better handling.
* **Future Work:** Apply machine learning models for deeper analysis and explore other aspects of the data.

## Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* WordCloud

## How to Use

1. Clone this repository.
2. Install the necessary libraries (see the notebook).
3. Open and run the Jupyter Notebook file to view the detailed analysis and results.

## Disclaimer

This project is for educational purposes only. The analysis and interpretations presented are based on the TMDB dataset and may not fully represent the entire film industry. The movie recommendations are based on the algorithms and data available and might not perfectly match individual preferences.
