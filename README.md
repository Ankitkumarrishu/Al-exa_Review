# 📦 Amazon Alexa Reviews Sentiment Analysis

A simple **Flask-based web application** to analyze **Amazon Alexa reviews** and determine their **sentiment**.

## Features

- Analyze Amazon Alexa customer reviews.
- Predict sentiment: Positive or Negative.
- Lightweight and easy-to-run Flask web app.
- Pre-trained model included for immediate use.

## Installation & Setup

### Clone the repository

```bash
git clone https://github.com/Ankitkumarrishu/Al-exa_Review.git
cd Al-exa_Review
```

Create & activate a Conda environment

```bash
conda create -n amazonreview python=3.10 -y
conda activate amazonreview
```

Install dependencies

```bash
pip install -r requirements.txt
```
Run the Flask app
```bash
flask --app api.py run
```

Access the app

Open your browser and go to:
```bash
http://localhost:5000
```

Notes

The previously reported issues have been fixed.

Ensure you download the latest .zip folder from the repository before running.

The app runs on port 5000 by default.

Repository Structure

```bash
├── api.py             # Main Flask app
├── model.pkl          # Pre-trained sentiment model
├── requirements.txt   # Python dependencies
├── README.md          # Project documentation
├── templates/         # HTML templates for Flask app
└── data/              # Dataset (if included)
```

How It Works

User submits an Amazon Alexa review.

The Flask app processes the text input.

The pre-trained model predicts the sentiment (positive or negative).

The result is displayed on the web interface.

Contribution

Fork the repository, make your changes, and create a pull request.

Suggestions and improvements are welcome!
