# Recipe Recommendation System

## Overview

This Recipe Recommendation System is a web application that suggests recipes based on user-provided ingredients, dietary preferences, flavor profiles, preparation time, and cooking time. The app leverages a dataset of Indian recipes and employs a simple filtering algorithm to recommend suitable recipes.

## Features

- Input your available ingredients and dietary preferences.
- Get recipe recommendations that match your criteria.
- Simple and user-friendly interface using Streamlit.

# Good News Filter

The **Good News Filter** is a Python-based application designed to scrape and curate positive news articles from the internet. Utilizing the News API, it fetches the latest headlines and articles, applying a sentiment analysis model to filter out articles that convey a positive sentiment. 

### Key Features:
- **Web Scraping:** The application retrieves articles from specified news sources or APIs, dynamically updating the content based on the latest available data.
- **Sentiment Analysis:** It employs a pre-trained sentiment analysis model to evaluate the emotional tone of the article titles, identifying those that are predominantly positive.
- **Curated Output:** Users receive a list of positive news articles, complete with titles, summaries, and links for further reading, helping to uplift spirits and promote a more optimistic view of current events.

### Usage:
Ideal for anyone looking to stay informed about uplifting news, the Good News Filterer can be easily integrated into other applications or used as a standalone tool, making it a valuable resource for individuals and organizations aiming to spread positivity in a world often filled with negative headlines.

# Cuss Word Censoring in Audio Files
This project processes an uploaded audio file, detects specified cuss words, and censors them by replacing them with silence or beeps. It uses OpenAI's Whisper model for transcription and the pydub library for audio manipulation.

## Usage
### Upload the Audio File: 
Run the code in a Jupyter Notebook or Google Colab. Use the file upload widget to upload your audio file in .mp3 or .wav format.
### Process the Audio: 
The code will: Transcribe the audio file using Whisper.
Detect cuss words from a predefined list.
Replace cuss words with silence.
Download Censored Audio: A download link for the censored audio file will be displayed. You can also play the censored audio directly in the notebook.




