# NLP Lemmatization-Based Question Matching

## Problem Statement
Different word forms (running, runs, ran) affect keyword matching 
between questions and passages. This project applies lemmatization 
to normalize word forms and improve matching accuracy.

## Dataset
Manually collected text passages on topics:
- Sports & Science
- Environment & Health
- Education & Finance

## What This Project Does
- Prepares 10 questions and 3 passages
- Applies lemmatization to both questions and passages
- Compares before (exact) vs after (lemmatized) keyword matching
- Shows improvement in match scores

## Tools & Libraries Used
- Python
- NLTK (WordNetLemmatizer)
- Jupyter Notebook

## How to Run
1. Open lemmatization_matching.ipynb in Jupyter Notebook
2. Run all cells
3. View before/after matching results

## Result
Lemmatization improved overall keyword matching score by normalizing
word forms like:
- behaviors → behavior
- technologies → technology
- medications → medication
