# NLP Repository 🚀

This repository contains my completed **Assignment 5** for CS 322 Data Science, focused on Natural Language Processing (NLP) tasks using the IMDB movie reviews dataset.

## Project Overview

The goal of this assignment is to perform sentiment analysis on movie reviews by:

- Loading and preprocessing the IMDB dataset of 50K movie reviews
- Conducting exploratory data analysis on the text
- Vectorizing text data using various techniques
- Training and tuning multiple classification models (including Naive Bayes)
- Evaluating model performance on a custom test set of student-written movie reviews

**Dataset Source**:  
[IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
Citation:  
Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). *Learning Word Vectors for Sentiment Analysis*. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).

## Notebook Contents

- **`Assignment5_NLP.ipynb`**: The main Jupyter notebook containing all tasks:
  1. Load the IMDB training dataset
  2. Create binary target column (`class`: 0 = negative, 1 = positive)
  3. Exploratory data analysis (word clouds, common words, etc.)
  4. Text vectorization (e.g., CountVectorizer, TF-IDF, etc.)
  5. Train and tune multiple models with cross-validation
  6. Process and predict on the custom test dataset
  7. Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices

## Test Dataset

The test set consists of **60+ student-written movie reviews** collected as part of the assignment:

- Each student wrote 5+ original movie reviews (roughly half positive, half negative)
- Reviews were saved as `.txt` files (e.g., `yourname_1_positive.txt`)
- All reviews were compiled into a single test set (provided later via a zip file)

Models trained on the IMDB dataset are evaluated on this real-world, student-generated test set.

## Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn (CountVectorizer, TfidfVectorizer, Naive Bayes, etc.)
- matplotlib, seaborn, wordcloud (for visualization)
- nltk or other text processing libraries as needed

