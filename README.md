## Project description:
The Film Junky Union, a new edgy community for classic movie enthusiasts, 
is developing a system for filtering and categorizing movie reviews. 
The goal is to train a model to automatically detect negative reviews. 

### Data description:
IMDB movie reviews with polarity labelling. 

### Goal:
Develop a model for classifying positive and negative reviews, with F1 score of at least 0.85.

### Steps performed:
- Exploratory Data Analysis
- Evaluation Procedure
- Normalization
- train/test split
- Testing different models

### Results:
- Best model: Model 1 - NLTK, TF-IDF and LR (with 0.88 F1 test score).
- NLTK and spaCy perform similarly.
- Logistic regretion is preforming better than LGBMClassifier.
