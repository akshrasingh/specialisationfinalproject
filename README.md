# Email Classification and Automated Response Web App

This Flask-based web application is designed to analyze emails, classify them into categories, generate automated responses, perform sentiment analysis, and check for grammatical errors. The app utilizes NLP models and tools to provide an intelligent interface for email handling.

## Features

- **Email Classification**: Classifies emails into categories such as "Job-Related", "Personal", "Document Checking and Editing", and "Professional".
- **Automated Reply Generation**: Generates automated responses based on the classification of the email content.
- **Sentiment Analysis**: Analyzes the sentiment of the email (positive, negative, or neutral) and provides the confidence level of the prediction.
- **Grammar Checking**: Identifies and corrects grammar issues in the email content.

## Technologies Used

- **Flask**: Web framework for building the app.
- **Transformers**: Hugging Face's pre-trained BERT model for sentiment analysis.
- **LanguageTool**: Grammar checking tool to identify and correct grammatical issues in the email content.
- **Python**: Programming language used for backend development.

## Requirements

1. Python 3.x
2. Install dependencies using `pip`:

   ```bash
   pip install -r requirements.txt


Clone the Repository
git clone https://github.com/your-username/email-analysis-app.git
cd email-analysis-app

Running the Application
Start the Flask app:
python app.py
