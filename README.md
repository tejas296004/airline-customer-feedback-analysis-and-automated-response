# Airline Customer Feedback Analysis & Automated Response

## About the Project

This project analyzes airline customer reviews to find critical negative reviews.

Python is used to clean the data, find common complaints, and select important negative reviews.

Google Gemini is then used to generate personalized and empathetic customer-support emails.

## What the Project Does

- Loads the airline review dataset.
- Cleans the review data.
- Identifies critical reviews using ratings.
- Finds common complaint keywords.
- Selects 3 detailed critical reviews.
- Generates customer-support responses using Google Gemini.

## Data Cleaning

The following steps were performed:

- Missing review values were handled.
- Non-numeric ratings were removed.
- Review title and review text were combined.
- Text was converted to lowercase.
- Special characters were removed.
- Extra spaces were removed.

## Critical Review Logic

Reviews with a normalized rating of **1 or 2** are considered critical.

This is done using simple Python rules.

No Machine Learning model is used.

## Generative AI

Google Gemini is used to generate short and empathetic apology emails for the selected critical reviews.

The AI is instructed to understand the customer's complaint and write a professional response.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries.
3. Keep `Airline_review.csv` in the same folder as the notebook.
4. Open the notebook in Jupyter.
5. Set the `GEMINI_API_KEY` environment variable.
6. Run the notebook cells from top to bottom.

## API Key

The Gemini API key is required for the Generative AI part.

The API key should not be shared or uploaded publicly.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Google GenAI
- Python

## Result

The project identifies critical customer complaints and uses Generative AI to create personalized customer-support responses.