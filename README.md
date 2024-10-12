# Google_playstore_UPIapps_review_analysis
Machine Learning For customer experience in financial services (Capstone Project) 2024 • Analyze customer sentiment expressed in Google Play Store reviews using a Bidirectional Encoder Representations from Transformers pre-trained model, thereby gaining insights into customer opinions and perceptions regarding the product or service offered.
# Machine Learning for Customer Experience in Financial Services (Capstone Project) 2024

## Overview

This project analyzes customer sentiment expressed in Google Play Store reviews of UPI (Unified Payments Interface) apps using a **Bidirectional Encoder Representations from Transformers (BERT)** pre-trained model. By applying Natural Language Processing (NLP) techniques, this project aims to gain insights into customer opinions and perceptions regarding the product or services offered by these apps in the financial sector.

---

## Features

- **Data Scraping**: Customer reviews were scraped from the Google Play Store using the `google-play-scraper` package to create a dataset for analysis.
- **Sentiment Analysis**: Using the pre-trained **BERT** model to classify the sentiment of each review into categories (positive, neutral, negative).
- **Data Visualization**: Visualize key insights and sentiment trends from the customer feedback using **Seaborn** and **Matplotlib**.
- **Customer Feedback Insights**: The project provides insights into how customers perceive various features and services of UPI apps, including security, ease of use, and reliability.

---

## Project Structure

- `Capstone.ipynb`: The main Jupyter Notebook file that contains the code for scraping, data preprocessing, and sentiment analysis.
- `data/`: Folder containing the scraped Google Play Store reviews dataset.
- `plots/`: Contains visualizations generated during the analysis.
- `README.md`: This file.

---

## Technologies Used

- **Python**: Main programming language used for data scraping, manipulation, and analysis.
- **Google Play Scraper**: A Python library used to scrape reviews from the Google Play Store.
- **Natural Language Processing (NLP)**: Employed for processing and analyzing text data using BERT.
- **BERT (Bidirectional Encoder Representations from Transformers)**: A state-of-the-art pre-trained transformer model used for sentiment classification.
- **PyTorch**: Used to load the pre-trained BERT model and fine-tune it on the dataset.
- **Pandas**: For data manipulation and cleaning.
- **Seaborn & Matplotlib**: Libraries used for data visualization.

---

## Dataset

The dataset consists of reviews scraped from various UPI applications on the Google Play Store. Each review includes:
- **Review Text**: The content of the review.
- **Rating**: A rating from 1 to 5 stars.
- **Timestamp**: Date and time the review was posted.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ML_Customer_Experience_Financial_Services.git
   cd ML_Customer_Experience_Financial_Services
