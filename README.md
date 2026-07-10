# Indian Language Word Frequency Analyzer

The Indian Language Word Frequency Analyzer is a web-based application designed to analyze textual data in multiple Indian languages by calculating word frequencies and presenting the results through an intuitive and interactive interface. The platform enables users to upload or enter text, process linguistic data, and gain meaningful insights through visual analysis.

## Overview

The increasing availability of multilingual digital content has created a need for efficient text analysis tools. This project provides a simple yet effective solution for analyzing word distributions across Indian languages. It performs text preprocessing, calculates word frequencies, removes unnecessary characters, and visualizes the results for easier interpretation.

The application combines a responsive frontend with a Python-based backend to deliver efficient natural language processing capabilities.

---

# Features

- Support for multiple Indian languages
- Text preprocessing and normalization
- Word frequency analysis
- Stop-word filtering
- Interactive data visualization
- Graphical representation of word distribution
- User-friendly web interface
- Fast and lightweight processing

---

# Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Backend

- Python
- Flask

## Libraries

- Pandas
- Matplotlib
- NumPy
- NLTK (where applicable)

## Data Storage

- JSON
- Text Files

---

# Project Structure

```text
Indian-Language-Word-Frequency-Analyzer/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   └── results.html
│
├── data/
│
├── app.py
├── requirements.txt
└── README.md
```

---

# System Architecture

## Frontend

The frontend is developed using HTML, CSS, and JavaScript to provide an intuitive interface for uploading text, viewing analysis results, and exploring graphical representations of word frequencies.

## Backend

The backend is implemented using Flask and is responsible for:

- Processing uploaded text
- Cleaning and preprocessing data
- Tokenizing words
- Calculating word frequencies
- Generating statistical summaries
- Returning processed results to the frontend

## Data Processing

The application performs several preprocessing operations, including:

- Removal of punctuation
- Case normalization
- Tokenization
- Stop-word removal
- Frequency calculation

---

# How It Works

1. The user uploads or enters text in an Indian language.
2. The backend preprocesses the text by removing unwanted characters and formatting inconsistencies.
3. The processed text is tokenized into individual words.
4. Word frequencies are calculated.
5. The results are displayed in both tabular and graphical formats.
6. Users can analyze the most frequently occurring words for further linguistic insights.

---

# Core Functionalities

## Text Processing

- Text cleaning
- Tokenization
- Stop-word filtering
- Language-aware processing

## Analysis

- Word frequency calculation
- Frequency ranking
- Statistical summaries

## Visualization

- Bar charts
- Frequency tables
- Interactive result display

---

# Installation

Clone the repository.

```bash
git clone https://github.com/jenildhorajiya12/indian-language-word-frequency-analyzer.git
```

Navigate to the project directory.

```bash
cd indian-language-word-frequency-analyzer
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

Run the Flask application.

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

# Future Enhancements

- Support for additional Indian languages
- Sentiment analysis
- Phrase and n-gram analysis
- Named Entity Recognition (NER)
- Interactive dashboards
- Downloadable analysis reports
- User authentication
- Database integration for storing analysis history

---

# Developers

**Jenil Patel**

**Harmi jadav**

The Indian Language Word Frequency Analyzer was designed and developed to demonstrate practical applications of natural language processing, multilingual text analysis, and web-based data visualization.

---

# License

This project is intended for educational, research, and portfolio purposes.

---

# Vision

The objective of this project is to provide an accessible platform for multilingual text analysis, enabling users to explore linguistic patterns and gain meaningful insights from textual data across Indian languages.