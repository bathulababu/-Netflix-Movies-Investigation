# Netflix Movies Investigation

This project investigates trends in Netflix movie durations over the years. It involves data handling, visualization, and analysis to understand how movie lengths have evolved.

## Project Description

The primary objective of this project is to analyze Netflix movie data to determine if movie durations have been decreasing over time. The analysis includes creating a DataFrame from provided data and visualizing the trend using a line plot and scatter plot.

## Data

The project utilizes a small dataset containing:

-   `years`: Years from 2011 to 2020.
-   `durations`: Corresponding movie durations in minutes.

Additional data from a Netflix dataset (`netflix_data.csv`) is used, which includes details like:

-   `title`: Movie title.
-   `country`: Country of origin.
-   `genre`: Movie genre.
-   `release_year`: Year of release.
-   `duration`: Duration of the movie.

## Methodology

1.  **Data Creation**:
    -   Creating lists for `years` and `durations`.
    -   Combining these lists into a dictionary.
    -   Creating a pandas DataFrame from the dictionary.
2.  **Initial Visualization**:
    -   Generating a line plot to visualize the trend of movie durations over the years.
    -   Adding a title to the plot for clarity.
3.  **Data Loading and Preparation**:
    -   Loading the `netflix_data.csv` dataset into a DataFrame.
    -   Displaying the first few rows of the DataFrame.
    -   Inspecting the data types of the columns.
4.  **Filtering Data**:
    -   Filtering the dataset to include only movies (i.e., `type == "Movie"`).
    -   Selecting relevant columns for analysis (`title`, `country`, `genre`, `release_year`, `duration`).
    -   Dropping rows with missing values.
5.  **Enhanced Visualization**:
    -   Creating a scatter plot to visualize movie `release_year` against `duration`.
    -   Adding a title to the scatter plot.
    -   Labeling the axes for clarity.
    -   Color-coding the plot by `genre` to observe genre-specific trends.
6.  **Analysis and Interpretation**:
    -   Analyzing the plot to identify patterns and trends in movie durations.
    -   Drawing conclusions about whether movies are getting shorter.

## Libraries Used

-   pandas
-   matplotlib.pyplot
-   seaborn

## Usage

To replicate this analysis:

1.  Ensure you have the required libraries installed:

    ```bash
    pip install pandas matplotlib seaborn
    ```

2.  Place the `netflix_data.csv` file in the same directory as the notebook.
3.  Run the Jupyter Notebook (`netflix-movies-investigation.ipynb`) to execute the code and reproduce the visualizations and analysis.

## Files

-   `netflix_data.csv`: Dataset containing Netflix movie information.
-   `netflix-movies-investigation.ipynb`: Jupyter Notebook containing the code and analysis.

## Key Insights

The analysis aims to provide insights into:

-   Trends in movie durations over the past decade.
-   The relationship between release year and movie duration.
-   Genre-specific patterns in movie lengths.

## Author

\[Naveen Babu Bathula]
