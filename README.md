# Sentiment Analysis of Honor of Kings Reviews on Play Store

This project analyzes user reviews for the game "Honor of Kings" on the Play Store, focusing on sentiment classification. The goal is to assess the sentiments of reviews, categorize them as positive, neutral, or negative, and gain insights into user feedback.

## Project Overview

This project involves:
- **Data Scraping**: Collecting reviews for the game "Honor of Kings" directly from the Play Store.
- **Sentiment Analysis**: Using machine learning models to classify the sentiment of the reviews.
- **Data Visualization**: Presenting sentiment analysis results using various visualizations to help interpret user opinions.

### Dataset

The project utilizes data scraped from the Play Store for the "Honor of Kings" game. The dataset includes user reviews, ratings, and sentiment labels, though the actual data is not provided due to file size constraints.

- **Dataset Files**:
  - `ulasan_honor_of_kings.csv`: Contains the reviews and ratings (assumed to be available locally).
  - `Scrapping_Dataset_Review_Honor_of_Kings.ipynb`: Jupyter notebook for scraping Play Store reviews.
  - `[Sunmission]_Sentimen_Analisis_Review_Honor_of_Kings_pada_Play_Store.ipynb`: Jupyter notebook for performing sentiment analysis and generating visualizations.

## Setup Instructions

Follow the steps below to set up and run this project.

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/DavinGhani/NLP-REVIEW-HOK
cd project-name
```

### 2. Install Dependencies
```
# Create a virtual environment (if not already created)
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

