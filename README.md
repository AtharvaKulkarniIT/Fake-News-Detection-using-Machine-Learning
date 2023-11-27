# Fake News Detection using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AtharvaKulkarniIT/Fake-News-Detection-using-Machine-Learning/blob/main/Fake_News_Detection.ipynb)

## Overview

This repository contains a Jupyter notebook for a Fake News Detection project using machine learning techniques. The notebook is designed to run on Google Colab, leveraging a GPU for accelerated processing.

## Prerequisites

Make sure you have the required libraries installed by running the following commands:

```bash
pip install pandas numpy matplotlib seaborn wordcloud nltk gensim plotly scikit-learn
```

## Contents

The notebook is divided into the following sections:

1. **Loading the Dataset**
   - Reads and loads the True and Fake news datasets from [Kaggle](https://www.kaggle.com/code/therealsampat/fake-news-detection).

2. **Setting up a target and merging datasets**
   - Adds a target column indicating whether the news is true (1) or fake (0).

3. **Checking the number of null values**
   - Identifies and handles null values in the dataset.

4. **Data Cleaning**
   - Removes stopwords and performs data cleaning.

5. **Exploratory Data Analysis (EDA)**
   - Analyzes and visualizes the distribution of true and fake news, most covered issues, word cloud and maximum word count in a title.

6. **Data Preprocessing**
   - Further cleans and prepares the data for model training.

7. **Model Building**
   - Utilizes four algorithms for training and evaluation:
      - Logistic Regression
      - Decision Tree Classifier
      - Gradient Boosting Classifier
      - Random Forest Classifier

8. **Manual Testing**
   - Allows users to input news for manual testing and provides predictions from the trained models.

9. **Hindi to English News Translation**
   - Translates Hindi news to English for testing.

## Usage

1. Open the notebook in Google Colab using the provided badge.
2. Run each cell sequentially to execute the code and observe the results.
3. Optionally, use the manual testing section to input news for predictions.

## Contributing

Feel free to contribute, provide feedback or report issues.
