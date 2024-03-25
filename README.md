# Movie Collection Prediction

## Overview
This repository contains Python code for predicting the collection (revenue) of movies based on various attributes such as marketing expense, production expense, multiplex coverage, budget, movie length, actor ratings, director ratings, critic ratings, social media metrics, and genre. The dataset used for this task includes detailed information about movies.

## Data Description
The dataset consists of the following columns:
- **Marketing_expense**: Expense incurred for marketing the movie.
- **Production_expense**: Expense incurred for production.
- **Multiplex_coverage**: Coverage of multiplexes for the movie.
- **Budget**: Budget allocated for the movie.
- **Movie_length**: Length of the movie in minutes.
- **Lead_ Actor_Rating**: Rating of the lead actor.
- **Lead_Actress_rating**: Rating of the lead actress.
- **Director_rating**: Rating of the director.
- **Producer_rating**: Rating of the producer.
- **Critic_rating**: Rating from movie critics.
- **Trailer_views**: Number of views for the movie trailer.
- **Time_taken**: Time taken for the movie to release.
- **Twitter_hastags**: Number of hashtags related to the movie on Twitter.
- **Avg_age_actors**: Average age of the actors in the movie.
- **Num_multiplex**: Number of multiplexes showing the movie.
- **3D_available**: Availability of the movie in 3D format.
- **Genre_Thriller**: Binary indicator for thriller genre.
- **Genre_Drama**: Binary indicator for drama genre.
- **Genre_Comedy**: Binary indicator for comedy genre.

## Contents
- **Movie_collection_Independent.csv**: CSV file containing independent variables (attributes) of the movies.
- **Movie_collection_Target.csv**: CSV file containing the target variable (collection) of the movies.
- **movie_collection_prediction.ipynb**: Jupyter Notebook containing Python code for data analysis and modeling.
- **README.md**: This README file providing an overview of the repository.

## Installation and Usage
To use this repository, follow these steps:
1. **Clone the Repository**: Clone or download this repository to your local machine.  `git clone https://github.com/your-username/movie-collection-prediction.git`
2. **Install Dependencies**: Install the required Python packages listed in the requirements.txt file using pip.    `pip install -r requirements.txt`
3. **Run the Jupyter Notebook**: Open the movie_collection_prediction.ipynb notebook in a Jupyter environment. Execute the code cells in the notebook to load the data, perform analysis, visualize the results, and build predictive models.

## Tutorial/How to Run
- **Check tutorial.md**

## Analysis Workflow
The analysis workflow in the Jupyter Notebook includes the following steps:
1. **Data Loading and Inspection**
2. **Data Cleaning and Preprocessing**
3. **Exploratory Data Analysis (EDA)**
4. **Model Building**
5. **Model Evaluation**

## Libraries Used
The analysis and modeling tasks are implemented using the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
[Farhan](https://github.com/FFFarhan)
