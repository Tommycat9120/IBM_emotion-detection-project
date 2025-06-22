# Emotion Detection Web App

This project is a Flask-based web application that detects emotions in a given text using IBM Watson's Natural Language Processing (NLP) service.

## 📌 Project Overview

The app allows users to input text through a simple web interface. It uses the Watson NLP Emotion Prediction API to return a set of emotion scores and identify the **dominant emotion** in the statement. 

If the input is blank or invalid, the app responds with a helpful error message.

---

## 🚀 Features

- Detects five emotions: **anger**, **disgust**, **fear**, **joy**, and **sadness**
- Identifies the **dominant emotion**
- Handles blank or invalid input with friendly error messaging
- Integrated unit tests for reliability
- PyLint-compliant (score: 10/10)
- Deploys on `localhost:5000`

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **API**: IBM Watson NLP – EmotionPredict endpoint
- **Testing**: `unittest`
- **Linting**: `pylint`
- **Deployment**: Localhost

---

## 📂 Project Structure
    ```final_project
    ├── EmotionDetection/
    │   ├── __init__.py/
    │   ├── emotion_detection.py/
    ├── static/
    │   └── backend/
    ├── templates/
    │   └── index.html/
    ├── server/
    ├── test_emotion_detection.py/
    ├── README.md/
    ```
---

## 🧪 Example Output

For the input:  
`"I love my life"`

The app returns:
For the given statement, the system response is
'anger': 0.0062,
'disgust': 0.0025,
'fear': 0.0092,
'joy': 0.9680 and
'sadness': 0.0497.
The dominant emotion is joy.
---
