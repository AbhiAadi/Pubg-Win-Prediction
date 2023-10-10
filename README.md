# PUBG Win Prediction with CatBoost

![PUBG Image]([(https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/a66d9aa2-f0a2-4e8d-9d73-4ba543ea1a50/dcvmu62-5c2b1cba-fed3-440d-8ce9-5e8787e0f08e.png/v1/fill/w_239,h_350/pubg__render__by_kindratblack_dcvmu62-350t.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTQ5OCIsInBhdGgiOiJcL2ZcL2E2NmQ5YWEyLWYwYTItNGU4ZC05ZDczLTRiYTU0M2VhMWE1MFwvZGN2bXU2Mi01YzJiMWNiYS1mZWQzLTQ0MGQtOGNlOS01ZTg3ODdlMGYwOGUucG5nIiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.1KLRq93GvAyQuOA1XKGBkCRsmVpLOiBwl82PfHauRrQ)]

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


