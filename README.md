# NBA Game Prediction Model using scikit-learn

This notebook builds an NBA game outcome prediction model using scikit-learn and data pulled from the nba_api package.

## Overview

The goal of this project is to predict whether a team will win or lose a game based on recent performance trends, using rolling/exponentially-weighted statistics from the last 20 games.

## Main Steps in the Notebook

- Load NBA game logs using nba_api

- Explore and visualize team performance data

- Engineer features using:

- last 20 games statistics per team

- exponential weighted averages to emphasize recent games

- Combine home vs away team stats into a single modeling dataset

- Visulize what features are most correlated with winning to be used for the model

- Train various machine learning models using various features 
    *   Only home team features
    * Only away team features
    * Logistic Regression, Random Forest, XG Boost
- Combined models into one final ensemble model
