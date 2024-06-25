# Netflix Data Analysis

## Overview
This project analyzes the Netflix dataset to extract insights about the content available on the platform. It covers various aspects such as content types, country-wise distribution, popular genres, top actors and directors, and the best time to release TV shows and movies.

## Dataset
The dataset used in this analysis is `netflix_titles.csv`, which includes information about the TV shows and movies available on Netflix as of the time of data collection.

## Analysis and Visualizations
The analysis is divided into several parts, each focusing on different aspects of the dataset:

### Basic Analysis
- **Handling Null Values**: Null values in categorical columns are replaced with 'Unknown' followed by the column name. Null values in continuous columns are replaced with 0.
- **Un-nesting Columns**: The `cast` and `listed_in` columns are un-nested to facilitate detailed analysis.
- **Removing Duplicate Rows**: Duplicate rows are removed to ensure data integrity.

### Categorical Variables Analysis
- **Content Types**: A count plot visualizes the distribution of content types (Movies vs. TV Shows).
- **Country-wise Distribution**: The top 20 countries by content count are displayed using a count plot.
- **Content Categories**: The top 15 content categories are displayed using a count plot.
- **Ratings Distribution**: A count plot shows the distribution of content ratings.

### Comparison of TV Shows vs. Movies
- **Top Countries for Movies and TV Shows**: Bar plots visualize the top 10 countries producing movies and TV shows.
- **Best Time to Release Content**: Analysis identifies the best week and month to release TV shows and movies based on historical data.

### Actor and Director Analysis
- **Top 10 Actors**: Bar plot visualizes the top 10 actors with the most appearances in movies and TV shows.
- **Top 10 Directors**: Bar plot visualizes the top 10 directors with the most movies and TV shows.

### Word Cloud for Genres
- **Genre Word Cloud**: A word cloud visualization highlights the most common genres in the dataset.

### Time to Add Movies to Netflix
- **Days to Add Movies**: Analysis determines the typical number of days it takes for a movie to be added to Netflix after its release.

## Results
- **Content Distribution**: The majority of the content on Netflix is movies, with the United States contributing the most content.
- **Popular Genres**: International Movies, Dramas, and Comedies are the most popular genres.
- **Release Timing**: The best week to release TV shows is week 27, and the best month is July. For movies, the best week is week 1, and the best month is also July.
- **Top Contributors**: The top actors and directors are identified based on the number of unique titles they have been associated with.
- **Typical Days to Add Movies**: It typically takes around 224 days for a movie to be added to Netflix after its release.

## Dependencies
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **WordCloud**: For generating word clouds.

## Repository Structure

- `NetflixCaseStudyScaler.ipynb`: Jupyter notebook containing the complete analysis and visualizations.
- `netflix_titles.csv`: Dataset used for the analysis (not included in this repository).

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook NetflixCaseStudyScaler.ipynb
    ```
4. Run the cells in the notebook to execute the analysis.

## Insights and Recommendations

### Insights

- **Content Distribution**:
  - The majority of content on Netflix is movies.
  - The United States and India are the top contributors of content.
- **Popular Genres**:
  - International Movies, Dramas, and Comedies are the most popular genres.
- **Release Timing**:
  - Best week to release TV shows: Week 27
  - Best month to release TV shows: July
  - Best week to release movies: Week 1
  - Best month to release movies: July
- **Top Contributors**:
  - Identified top actors and directors based on the number of unique titles.
- **Typical Days to Add Movies**:
  - It typically takes around 224 days for a movie to be added to Netflix after its release.

### Recommendations

1. **Content Strategy**:
   - Focus on acquiring and producing more movies, especially in popular genres like International Movies and Dramas.
   - Consider focusing on content from top contributing countries, especially the United States and India.
2. **Release Strategy**:
   - Plan major releases (both TV shows and movies) in July to maximize engagement.
3. **Talent Acquisition**:
   - Collaborate with top actors and directors who have a proven track record on Netflix.

## Conclusion

This project provides a comprehensive analysis of the Netflix dataset, revealing key insights into content distribution, popular genres, top contributors, and optimal release times. These findings can inform strategic decisions for content acquisition, production, and release planning.

---

