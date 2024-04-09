# PLAGIARISM ANALYZER

## Overview
This is a simple plagiarism checker built with Streamlit and scikit-learn's TfidfVectorizer. The application allows users to input three texts (up to 5000 characters each) and calculates the pairwise cosine similarity between them to identify potential plagiarism. It also provides a percentile score for each pair of texts.

## Features
- Input Three Texts: Users can enter three texts through text areas in the user interface.
- Check Plagiarism: Clicking the "Check Plagiarism" button triggers the plagiarism check using cosine similarity.
- Percentile Score: The application calculates the percentile of plagiarism scores and displays them for each pair of texts.

## Usage
1.Enter text in the three provided text areas.
2.Click the "Check Plagiarism" button to initiate the plagiarism check.
3.View the percentile scores displayed for each pair of texts.

## Working
Install the required dependencies:
pip install streamlit scikit-learn numpy

Run the Streamlit app:
streamlit run plagiarism_checker.py

## Output
when we run the code in terminal with steamlit run filename.py then the terminal will provide with the local host link, where we can see the website.

<img src="C:\Users\nikit\OneDrive\Pictures\Screenshots\Screenshot 2024-02-23 214825.png"/>
