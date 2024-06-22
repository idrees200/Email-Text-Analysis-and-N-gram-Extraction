# Email Text Analysis and N-gram Extraction

This Python script (`email_text_analysis.py`) demonstrates various tasks related to email text analysis and N-gram extraction using natural language processing (NLP) techniques.

## Overview

The script performs the following tasks:

1. **Data Loading and Tokenization:**
   - Loads the email dataset (`emails.csv`) using pandas.
   - Tokenizes each email text into individual words using NLTK's `word_tokenize`.

2. **N-gram Extraction:**
   - Defines functions to extract N-grams (bigrams, trigrams, and higher-order N-grams) from tokenized email text.
   - Calculates frequency distributions of N-grams using NLTK's `ngrams` and `FreqDist`.

3. **Conditional Frequencies:**
   - Computes conditional frequencies of bigrams and trigrams using NLTK's `ConditionalFreqDist`.

4. **Probability Estimation:**
   - Estimates the probability of specific bigrams occurring using conditional frequencies.

5. **Visualization:**
   - Visualizes the frequency distribution of N-grams using matplotlib.
   - Plots log-log graphs to illustrate the distribution of N-gram frequencies.

6. **Statistical Measures:**
   - Uses NLTK's `BigramAssocMeasures` to compute Pointwise Mutual Information (PMI) scores for significant bigrams.

7. **Dependencies:**
   - Requires Python 3.x, pandas, NLTK, matplotlib, and numpy.
   - Install dependencies using pip:
     ```
     pip install pandas nltk matplotlib numpy
     ```

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/email-text-analysis.git
   cd email-text-analysis
