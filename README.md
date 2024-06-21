# FIFA World Cup Forecaster

## Description
This project aims to predict the winners of the 2022 FIFA World Cup based on historical data, team statistics, and player ratings. We used various machine learning models, including logistic regression, decision trees, bagging, random forests, and XGBoost, to train our models on data from the 2010, 2014, and 2018 World Cups.

## Data

The data used in this project includes:

- Team and player information for the 2010, 2014, 2018, and 2022 World Cups
- Player statistics from the FIFA video game
- Match results from the 2010, 2014, and 2018 World Cups

The data was scraped from various sources and preprocessed to create a design matrix suitable for training the models.

## Models

We implemented and compared the following models:

1. Logistic Regression
2. Ordinal Logistic Regression (Threshold Model)
3. Decision Tree
4. Bagging Decision Tree
5. Random Forest
6. XGBoost with SMOTE

The best-performing model was the Random Forest, which achieved a test accuracy of 0.596.

## Usage

To run the project, follow these steps:

1. Clone the repository: `git clone https://github.com/maysoshi/world-cup-forecaster.git`
2. Run the Jupyter Notebook or Python scripts to train the models and make predictions.

## Results

Our final model simulated the 2022 World Cup using the Random Forest classifier. The predicted results can be found in the `results` directory or viewed in the Jupyter Notebook.

## Future Work

Potential improvements and future work include:

- Augmenting the dataset by scraping from additional sources
- Trying different feature engineering techniques
- Exploring other ensemble methods and deep learning models
- Incorporating more advanced techniques for handling imbalanced data

## Collaborators

- Omar Abdel Haq
- Elie Eshoa
- Ibrahim Suat Evren
- Mari Kikuta
- Mayesha Soshi

## Acknowledgements 
This project was completed as part of Computer Science 109a at Harvard University.
