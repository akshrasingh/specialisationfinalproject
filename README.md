# Automated Email Sentiment Analysis and Reply Generation

This project is a Flask-based web application that automates the process of analyzing email content for classification, sentiment analysis, grammar checking, and automated reply generation. It utilizes natural language processing models and libraries like Hugging Face Transformers, TensorFlow, and LanguageTool.

## Features
### Email Classification
Categorizes email content into predefined categories like:
- "Job-Related"
- "Personal"
- "Document Checking and Editing"

### Automated Reply Generation
Generates contextually appropriate replies based on the email classification.

### Sentiment Analysis
Determines the sentiment (positive, neutral, or negative) of the email content.

### Grammar Checking
Highlights grammatical issues and provides corrected text.

## Installation

### Prerequisites
- Python 3.9 or above
- pip (Python package manager)
  
### Install Required Packages
pip install -r requirements.txt
Run the following command to install the necessary Python libraries:

### Run the  python file 
Navigate to the project directory and run the Flask app:
python app.py
Open a web browser and go to:
http://127.0.0.1:5000

### Directory structure
project/
├── app.py                # Main Flask application
├── templates/
│   └── index.html        # HTML template for the web interface
├── static/               # Folder for static assets (CSS, JS, images)
└── style.css 
# Dependencies for the project
pip freeze > requirements.txt

Output:

![image](https://github.com/user-attachments/assets/012855b2-35bf-4814-9078-ebc5f57b7b47)

![image](https://github.com/user-attachments/assets/a1f0f729-8117-473e-9f22-931edb2da554)

![image](https://github.com/user-attachments/assets/5e27cf0c-4fe8-4b22-84bc-4ea2fcd65ad9)


# Training the model -backend







