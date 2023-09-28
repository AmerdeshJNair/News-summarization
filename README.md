# News Summarizer Program

This program utilizes Python with the tkinter library to create a simple GUI-based news summarizer tool. It uses various libraries such as nltk, textblob, and newspaper to extract information from a provided URL and generate a summary of the news article.

## How to Use the Program

1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:
   ```
   pip install textblob nltk newspaper3k
   ```
3. Run the program by executing the Python script.

## Program Components

- `import tkinter as tk`: Importing the tkinter library for GUI creation.
- `import nltk`: Importing the Natural Language Toolkit for text processing.
- `from textblob import TextBlob`: Importing the TextBlob class for text analysis.
- `from newspaper import Article`: Importing the Article class from the newspaper library for web scraping articles.
- `import textblob`: Importing the textblob module for text analysis.

The program defines a function `summarize()` that extracts and displays the title, author, publishing date, and summary of a news article from a provided URL.

- `root`: Creating the main GUI window using tkinter.
- Labels and Text widgets: Displaying labels and text fields for input and output.
- `summarize()`: Function to summarize the news article.
- `tk.Button`: Creating a button to trigger the summarization process.

## Running the Program

1. Run the program by executing the script in a Python environment.
2. Enter the URL of a news article in the provided text field.
3. Click the "Summarize" button to generate the article summary and display it in the GUI.
