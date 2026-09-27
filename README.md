# Amazon Business Entity Resolution

## Overview

This project focuses on matching business entities from different
data sources and identifying records that represent the same business.

## Objective

The main objective is to match entities from Source 1 with their
corresponding entities in Source 2 and Source 3.

## Approach

1. Data preprocessing
2. Business name normalization
3. Exact matching
4. Candidate generation
5. Feature engineering
6. Machine learning based matching
7. Final entity resolution

## Features Used

- Name similarity
- Address similarity
- Name token similarity
- Address token similarity
- Number overlap
- Country match
- Source 1 address missing indicator
- Candidate address missing indicator

## Machine Learning Model

Random Forest Classifier

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- DuckDB
- Jupyter Notebook
- Kaggle

## Project Files

### amazon_entity_resolution.ipynb

Complete project notebook containing preprocessing,
candidate generation, feature engineering, model training,
and entity matching.

### requirements.txt

Contains the Python libraries required to run the project.

### .gitignore

Specifies files and folders that should not be uploaded
to the GitHub repository.

## Dataset

The original challenge dataset is not included in this repository.
It was provided through the challenge/Kaggle environment.

## Results

The project generates entity matching results and candidate pairs
using machine learning based entity resolution techniques.

## Author

Harsh Nagayach