# Parser
Create an AI that parse the sentence structure or syntax


## Objective

Create an AI that:
1. Parses sentences to determine their structure.
2. Extracts noun phrases to help understand what a sentence is about.

Parsing is a key task in natural language processing, where sentence structure is analyzed using context-free grammar rules.

## Project Overview

This project involves building an AI to parse sentences and extract **noun phrases** using **context-free grammar** and **Python's NLTK library**.


### Key Functions

1. **`preprocess`**: Tokenizes a sentence and returns a list of lowercase words, excluding non-alphabetic words.
2. **Grammar Rules**: Update `NONTERMINALS` to handle complex sentence structures. The rules start with `S ->` for sentences, and use `NP` for noun phrases.
3. **`np_chunk`**: Accepts a syntax tree and extracts noun phrase chunks (smallest noun phrases that don't contain others).

## Usage
Requires Python(3) and Python package installer pip(3) to run:
pip3 install -r requirements.txt

run : $ python parser.py
