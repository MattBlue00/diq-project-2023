# Data and Information Quality Project - AY 2023/2024

The objective of this project was to test the effects of different types of data pollution on the performance of various Machine Learning algorithms.

Specifically, this project documents the effects of the **Duplication**, and the **Variable types** issues in algorithms for Classification.

## Project Setup

This project unfolds in five steps:
1. Data Collection
2. Data Pollution
3. (Polluted) Data Analysis and Evaluation
4. Data Preparation
5. (Cleaned) Data Analysis and Evaluation

Our task was to design and develop the *pollution* and *preparation* tasks: This process required engineering both the functions to interact with data, and the experiments that could yield the most interesting results in our assigned scenario.

The dataset for this year's projects was a fully numeric, randomly generated dataset using sklearn's `make_classification` function.

## Data Pollution

For this step, we designed pollution functions that would inject non-exact duplicates, and functions that would append new correlated/non-correlated features to all the tuples of the dataset.

> Given the scarse interpretability of our dataset, we designed pollution functions to resemble some possible real-world scenarios.

The following is a brief overview of the functions, for a more comprehensive look, please refer to the notebooks.

