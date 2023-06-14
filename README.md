# Movie Data Analysis

![Movie Data Analysis](https://drive.google.com/uc?export=view&id=1HjFetQyX2wR3dOv7USLOnUzgrQ6NqrPv)


## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Analysis](#analysis)
- [Results and Conclusions](#results-and-conclusions)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Contact Information](#contact-niformation)

## Introduction
Welcome to the Movie Data Analysis project! This project aims to analyze a dataset of movies and gain insights into various aspects such as revenue, budget, runtime, genre, and director's influence on movie ratings. By performing exploratory data analysis, we can uncover interesting trends and patterns within the movie industry.

## Dataset
The dataset used for this analysis contains information about thousands of movies, including their titles, directors, genres, release years, budgets, revenues, ratings, and more. The dataset provides a comprehensive overview of the movie landscape and serves as the foundation for our analysis.

## Installation
To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/bright136/TMDB-Movies-Data-Analysis.git`
2. Navigate to the project directory: `TMDB-Movies-Data-Analysis`


## Usage


1. Open the Anaconda terminal.

2. Execute the following command to create a new Conda environment named `myenv`:

```
conda create --name myenv --file requirements.txt
```

3. Activate the environment by running the appropriate command based on your operating system:

   - For Windows:
     ```
     conda activate myenv
     ```

   - For Linux and macOS:
     ```
     source activate myenv
     ```


4. Now you can use the newly created Conda environment with the installed libraries for your project.

Remember to replace `myenv` with the desired name for your Conda environment.

5. Run the command in the terminal

                jupyter notebook

5. Ensure that the dataset file (`datasets/tmdb-movies.csv`) is placed in the project's root directory.
6. Run the main Notebook: `data-analysis-on-tmdb-data.ipynb`
6. Explore the generated visualizations and analysis results.


## Project Structure
The project is organized into several main sections:

1. Data Loading and Cleaning: The dataset is loaded into a Pandas DataFrame, and any necessary data cleaning and preprocessing steps are performed to ensure the data is in a suitable format for analysis.

2. Exploratory Data Analysis: Various exploratory data analysis techniques are employed to gain insights into the dataset. This includes examining statistical measures, visualizing distributions, exploring correlations between variables, and identifying trends and patterns.

3. Analysis and Visualization: The dataset is analyzed from different angles to answer specific questions and provide insights. This includes analyzing the relationship between factors such as popularity, revenue, budget, runtime, genre, and director. Visualizations such as bar plots, scatter plots, and histograms are generated to effectively communicate the findings.


## Analysis
The analysis performed in this project covers several key aspects of the movie industry. Here are some highlights:

1. **Correlation between Popularity and Revenue**: We explored the relationship between movie popularity and revenue, finding a slight positive correlation. Visualizations were created to illustrate this relationship.

2. **Influence of Budget on Revenue**: By examining the impact of movie budgets on revenue, we discovered that movies with higher budgets tend to generate higher profits. This relationship was visualized through scatter plots and statistical measures.

3. **Top Movies by Profit**: We identified the top five movies based on profit and provided details such as their titles, directors, genres, release years, and movie ratings. A bar chart visualized the profits of these movies.

4. **Movie Ratings**: We analyzed the movie ratings and identified the top-rated movies, their directors, and the genres associated with high ratings. Bar charts and tables were used to present this information.

5. **Director Analysis**: We explored the directors who produced the most movies within the dataset and calculated their average movie ratings. Bar charts showcased the number of movies produced by each director and their corresponding average ratings.

6. **Genre Analysis**: We investigated the genres that received the highest movie ratings and created a bar chart to display the average ratings for each genre.

These are just a few examples of the analyses performed in this project. For more detailed insights, please refer to the analysis section in the code.


## Results and Conclusions
Here are some of the key findings and conclusions from the analysis:

- There is a positive correlation between popularity and revenue, indicating that popular movies tend to generate higher revenue.
- Movies with high vote counts also tend to have higher revenue, suggesting that movies with more audience engagement are more financially successful.
- Movies with higher budgets generally generate higher profits. Additionally, movies with longer runtimes tend to have higher budgets.
- The top five movies based on profit are "Avatar," "Star Wars: The Force Awakens," "Titanic," "Jurassic World," and "Furious 7." "Avatar" directed by James Cameron stands out as the highest-grossing movie.
- "The Shawshank Redemption" directed by Frank Darabont and "Stop Making Sense" directed by Jonathan Demme have the highest movie ratings.
- Documentary movies tend to receive higher ratings on average.
- Steven Spielberg, Clint Eastwood, Woody Allen, Ridley Scott, and Ron Howard are among the most prolific directors during the analyzed period, with each having directed a significant number of movies. These directors have average movie ratings ranging from 6.5 to 6.8.

These conclusions provide valuable insights into the movie industry, highlighting the relationships between different factors and their impact on revenue, popularity, and ratings.

## Future Enhancements
- Conducting a more detailed genre analysis by exploring genre combinations and their impact on revenue, popularity, and ratings.
- Analyzing the relationship between release date and revenue/popularity to identify potential trends or seasonal patterns.
- Incorporating machine learning techniques to build predictive models for revenue or movie ratings based on available features.
- Exploring additional external datasets, such as demographic information or critical reviews, to gain deeper insights into audience preferences and critical reception.


## Contributing
All contributions to enhance the analysis and expand the scope of this project are welcomed. If you have any suggestions or improvements, please submit a pull request or open an issue. 

## Contact Information

<table>
  <tr>
    <th>Name</th>
    <th>Twitter</th>
    <th>LinkedIn</th>
    <th>GitHub</th>
    <th>Hugging Face</th>
  </tr>
  <tr>
    <td>Bright Eshun</td>
    <td><a href="https://twitter.com/bright_eshun_">@bright_eshun_</a></td>
    <td><a href="https://www.linkedin.com/in/bright-eshun-9a8a51100/">@brighteshun</a></td>
    <td><a href="https://github.com/Bright136">@bright136</a></td>
    <td><a href="https://huggingface.co/bright1">@bright1</a></td>
  </tr>
</table>