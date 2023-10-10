# PUBG Win Prediction with CatBoost

![PUBG Image]([link_to_your_image.png][(https://www.google.com/imgres?imgurl=http%3A%2F%2Fm.gettywallpapers.com%2Fwp-content%2Fuploads%2F2020%2F01%2FPUBG-Wallpaper-For-Phone.jpg&tbnid=1NL7GpB52eZnVM&vet=12ahUKEwjihuOMpeuBAxW96DgGHaSUAMQQMygIegUIARCAAQ..i&imgrefurl=http%3A%2F%2Fm.gettywallpapers.com%2Fpubg-wallpaper%2F&docid=4Dkk4_WgkeGhmM&w=1080&h=1920&q=pubg%20image&ved=2ahUKEwjihuOMpeuBAxW96DgGHaSUAMQQMygIegUIARCAAQ)](https://www.google.com/imgres?imgurl=https%3A%2F%2Fi.pinimg.com%2F236x%2F27%2F7b%2F03%2F277b03c0114dc931a16f6183b8be231e.jpg&tbnid=JJ6xkflJzHuhPM&vet=12ahUKEwjihuOMpeuBAxW96DgGHaSUAMQQMygqegUIARDQAQ..i&imgrefurl=https%3A%2F%2Fwww.pinterest.com%2Fsujanshrestha_%2Fpubg%2F&docid=TKMpUPcKoR8y5M&w=236&h=472&q=pubg%20image&ved=2ahUKEwjihuOMpeuBAxW96DgGHaSUAMQQMygqegUIARDQAQ))

## Overview

This project aims to predict the winning chances of players in the popular online game PUBG (PlayerUnknown's Battlegrounds) using the CatBoost machine learning algorithm. We utilize data from Kaggle to build and evaluate the predictive model.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- Python (>=3.6)
- Jupyter Notebook (optional but recommended)

### Data Source

The dataset used for this project can be accessed from Kaggle:
[Link to PUBG dataset on Kaggle](https://www.kaggle.com/datasets/ashishjangra27/pubg-games-dataset)

### Data Wrangling

To prepare the data for modeling, we perform the following data wrangling steps:

- Loading the dataset
- Performing the required operation on data for data cleaning
- Handling missing values (if any)
- Feature engineering
- Encoding categorical variables (if any)
- Splitting the data into training and testing sets

### Model Training

We use the CatBoost algorithm, a gradient boosting framework, to build our predictive model. The model is trained on the training dataset and tuned for optimal performance by appling the grid search method to get optimised hyperparameters.

### Evaluation

We evaluate the model's performance using suitable metrics, such as RMS and r2 score.


