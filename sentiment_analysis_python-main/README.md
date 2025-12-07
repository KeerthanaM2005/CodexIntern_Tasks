## SENTIMENT ANALYSIS WEB APP

* A complete web-based sentiment analysis platform built with Flask (Python) for backend processing and React for frontend interaction.
* This tool allows an admin to analyze individual text entries or process multiple records via CSV upload, stores the results securely in a database, and provides insights for monitoring trends in user feedback.

## PURPOSE OF THE PROJECT

* Organizations often receive large volumes of feedback, reviews, or comments, and need to understand overall sentiment to improve their services.
* This system ensures that only authorized admins can submit data for analysis, keeping sensitive user information safe.
* By measuring polarity, subjectivity, and overall sentiment (positive / neutral / negative), businesses can identify patterns and make informed decisions.

## KEY FEATURES

* Evaluate sentiment (polarity & subjectivity) of a single text input
* Process multiple texts at once through CSV file upload
* Categorize each entry as Positive, Neutral, or Negative
* Save all results to a MySQL database for future reference
* Admin-only access for all analysis and data uploads
* Frontend developed using React; backend uses Flask, TextBlob, and MySQL

## TECHNOLOGIES AND TOOLS

Backend: Python, Flask, TextBlob, MySQL (mysql-connector-python)
Frontend: React, Axios
Additional Tools: Flask-CORS for cross-origin requests, CSV utilities for bulk upload

## RUNNING THE APPLICATION
Start the Backend (Flask)
 * cd backend
 * pip install -r requirements.txt
 * python app.py

Start the Frontend (React)
 * cd frontend
 * npm install
 * npm start

## USAGE AND OUTPUT

After logging in as an admin:

Input a single text and receive a sentiment analysis
→ Displays polarity, subjectivity, and sentiment classification

Upload a CSV file to process multiple records simultaneously
→ Results are shown in the app and stored in the database

Access historical sentiment data for reporting and visualizations (graphs)
