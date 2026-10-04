# 🤖 Customer Support AI Chatbot

NLP-based conversational assistant that classifies customer messages into support intents and returns appropriate responses through a Flask web application.

## Capabilities
- Structured intent taxonomy.
- Text cleaning and normalization.
- NLTK preprocessing.
- TF-IDF feature extraction.
- Supervised intent classification.
- Confidence-aware prediction and fallback handling.
- Flask REST/web interface.

## Example intents
Billing • Refunds • Cancellations • Account Support • Technical Support • Order Status

## Architecture
```
Customer Message
      ↓
NLP Preprocessing
      ↓
TF-IDF
      ↓
Intent Classifier
      ↓
Confidence Check
      ↓
Response / Fallback
```

## Tech Stack
Python • NLTK • Scikit-Learn • TF-IDF • Flask

## Run
```bash
pip install -r requirements.txt
python chatbot.py
```

Open `http://127.0.0.1:5000`.

**Future Interns Machine Learning Internship — Task 3**