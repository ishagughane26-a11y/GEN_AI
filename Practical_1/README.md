NLP Analysis Studio

An interactive Natural Language Processing (NLP) application built with Python, Streamlit, NLTK, and spaCy.

The application provides a simple interface for performing multiple NLP operations on user-provided text.

👩‍💻 Student

Isha Gughane

✨ Features

The application supports the following NLP operations:

Sentence Segmentation

Word Tokenization

Stop Word Removal

Stemming

Lemmatization

Part-of-Speech (POS) Tagging

Named Entity Recognition (NER)

Dependency Parsing

Noun Phrase Chunking

Run All Steps

🛠️ Technologies Used

Python

Streamlit – interactive web interface

NLTK – text preprocessing and linguistic analysis

spaCy – NLP processing, NER, dependency parsing, and noun chunks

📁 Project Structure

Practical_1/
│
├── nlp_app.py
├── README.md
└── images/

⚙️ Installation

Install the required Python packages:

pip install streamlit nltk spacy

Download the spaCy English language model:

python -m spacy download en_core_web_sm

NLTK resources are downloaded automatically by the application when required.

▶️ How to Run

Open a terminal in the project directory and run:

streamlit run nlp_app.py

The application will open in your browser.

🔄 NLP Workflow

Input Text
    ↓
Sentence Segmentation
    ↓
Word Tokenization
    ↓
Stop Word Removal
    ↓
Stemming / Lemmatization
    ↓
POS Tagging
    ↓
Named Entity Recognition
    ↓
Dependency Parsing
    ↓
Noun Phrase Chunking

📌 Example Input

Apple Inc. is planning to open a new office in Bangalore next year.
Tim Cook announced this during a press conference in California.

The application analyzes this text and displays the results according to the selected NLP operation.

🎯 Objective

The objective of this practical is to understand and demonstrate the major stages of an NLP pipeline using Python libraries and an interactive Streamlit interface.

👩‍💻 Author

Isha Gughane

NLP Practical Project
