# Mall Data Analysis

## Project Description
In this project, I explore and analyze a dataset containing mall customer reviews. The objective is to extract meaningful insights from this dataset such as common features, top pros and cons, distribution of reviews based on ratings, and total number of reviews analyzed per data source.

##Dataset Description
The dataset includes the following columns:

1. web-scraper-order
2. product-link
3. product-name
4. product-price
5. asin
6. rating-count
7. rating-avg
8. review-page-link
9. review-date
10. review-text
11. review-author
12. review-rating

## Technologies Used

- Python
- Pandas
- Scikit-Learn
- NLTK
- Numpy
- Matplotlib
- Plotly
- Seaborn
- spacy
- WordCloud

## Features
1. Data Loading & Exploratory Data Analysis (EDA) of the dataset to identify common features.
2. Identification of the top 5 pros and cons in the reviews using sentiment analysis.
3. Calculation of the percentage distribution of reviews based on ratings.
4. Aggregation of the total number of reviews analyzed per data source.

##  Text-preprocessing steps

- Convert all Characters to Lowe Case.
- Remove Stopwords.
- Remove Punctuation.
- Stemmening.
-Lemmatization.

# Featurization
1. TF-IDF
2. T-SNE

## Model Training and Evaluation

1. Applying LogisticRegression Using GridSearch
2. Applying DesisionTree with GridSearch
3. Applying ExtraDecisionTrees with GridSearch ( Was The Best Accuracy)

## How to Run the Project

1. Clone this repository.
2. Download the dataset from Kaggle and put it in the same directory as the notebook.
3. Install the necessary Python packages. You can do this by running `pip install -r requirements.txt` (if you have pip installed) or `conda install --file requirements.txt` (if you're using the Anaconda distribution of Python).
4. Open the Jupyter notebook and run the cells to see the project in action.

# Authors and Acknowledgment
- Independent project for the client (srikesh.datta@piovis.com).
- Copy Write By Mostafa Tehamer.


