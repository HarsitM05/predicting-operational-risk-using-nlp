# README: Predicting Operational Risk Using NLP

## Project Overview
This project focuses on using Natural Language Processing (NLP) techniques to construct a cybersecurity risk measure from SEC 10-K filings. By analyzing text data from financial reports, we aim to assess the impact of cybersecurity risks on the market.

## Objectives
- Extract cybersecurity-related text from SEC 10-K filings.
- Develop a cybersecurity risk measure based on identified sentences.
- Perform descriptive analysis to observe trends across industries.
- Derive financial insights based on cybersecurity risk exposure.

## Technologies Used
- **Python** (primary programming language)
- **NLTK / Stanza** (for NLP processing)
- **Pandas & NumPy** (for data manipulation and computation)
- **Plotly** (for data visualization)
- **Jupyter Notebook** (for interactive execution)

## Installation
To set up the project environment, install the required dependencies:
```bash
pip install nltk pandas numpy plotly
```

## Methodology
1. **Preparing Text Data**: Tokenize sentences from 10-K filings.
2. **Keyword-Based Extraction**: Identify sentences related to cybersecurity risks.
3. **Risk Measure Construction**: Compute risk scores using:
   - Ratio of cybersecurity-related sentences to total sentences.
   - Absolute count of cybersecurity-related sentences.
4. **Descriptive Analysis**: Compute statistical measures and visualize trends from 2015-2023 across industries.

