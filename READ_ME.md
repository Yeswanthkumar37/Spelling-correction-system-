# Probabilistic Spell Checker using Python and NLTK

This project implements a simple yet effective probabilistic spell checker using Python and Natural Language Processing techniques. It suggests spelling corrections for a given word based on edit distances and word probabilities learned from a text corpus.

## Features

- Tokenizes and preprocesses a raw text file to extract vocabulary
- Computes word frequencies and unigram probabilities
- Generates correction candidates using single and double edit distance (insertion, deletion, replacement, transposition)
- Ranks suggestions based on their probability of occurrence
- Modular function design for easy debugging and extension

## Libraries Used

- `nltk` (Natural Language Toolkit): Tokenization, Lemmatization, and WordNet resources
- `re`: Regular expressions for text preprocessing
- `collections.Counter`: Word frequency counting
- `typing`: Type hints for better code clarity

## File Structure

- `final.txt`: Input corpus used to build vocabulary and compute probabilities (you must provide this)
- `spell_checker.ipynb`: Jupyter notebook containing all functions and logic
- `README.md`: Project overview and usage instructions

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/spell-checker.git
   cd spell-checker
