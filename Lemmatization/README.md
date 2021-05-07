# Lemmatization is a process to convert sentence into its root form.

For example:
- Performs -> Perform
- Better -> Good

It's better than Stemmer. Stemmer can turn "Better" to "Bett"

## NLTK lemmatization
  Better with individual words. Performs poorly on sentence.

## SpaCy lemmatization
  Can transform "Best" to "Good"
  Parallel Lemmatization using **joblib** library

## Gensim lemmatization
  Allows only the ‘JJ’, ‘VB’, ‘NN’ and ‘RB’ tags. That means "They" can get vanished.
