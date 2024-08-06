# chat-bot
A simple chatbot using NLTK, Scikit-learn, and Tkinter to fetch and process Wikipedia pages for generating responses

# Chatbot using NLTK, Scikit-learn, and Tkinter

This project implements a simple chatbot using Natural Language Processing (NLP) techniques. The chatbot fetches and processes Wikipedia pages, utilizes TF-IDF Vectorization, and employs cosine similarity to generate responses.

## Features
- Fetches Wikipedia pages to provide accurate responses.
- Utilizes TF-IDF Vectorization for text processing.
- Uses cosine similarity to find the most relevant responses.
- Built with a user-friendly GUI using Tkinter.
- Any wikipedia page can be imported to the bot to generate answers from there

## Requirements
- Python 3.x
- NLTK
- Scikit-learn
- Tkinter
- Wikipedia-API

## Installation
1. Install the required packages:
    ```bash
    pip install nltk scikit-learn wikipedia-api
    ```

## Usage

1. Run the `textbot.py` script:
    ```bash
    python textbot.py
    ```

2. A GUI window will appear. Type your questions in the input field and press Enter to get responses from the chatbot.

## Project Structure
- `textbot.py`: Main script that runs the chatbot.
- `chatbot (1).txt`: Contains sample dialogues for training/testing.


