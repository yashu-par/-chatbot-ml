# ML Chatbot — Intent Classification

A chatbot built using Machine Learning and Deep Learning (RNN/LSTM) that understands user intent and gives smart responses.

## What does this chatbot do?

This chatbot identifies user intent and gives appropriate responses. It supports 11 intents: greeting, bye, price, help, order, order_status, return, hours, location, thanks, about.

## Technologies Used

- Python 3.11
- Scikit-learn — ML models
- TensorFlow / Keras — RNN/LSTM model
- Pandas and NumPy — Data processing
- Groq API — LLM integration
- Jupyter Notebook — Development environment

## Model Results

- Naive Bayes: 88.2%
- Logistic Regression: 85.0%
- Random Forest: 74.1%
- LinearSVC: 88.4% (Best)
- RNN / LSTM: 90%+

## Dataset

- Total examples: 440
- Intents: 11
- Examples per intent: 40
- Language: English

## How to Run

1. Clone the repository
2. Install dependencies: pip install scikit-learn pandas numpy tensorflow groq python-dotenv
3. Create .env file and add your Groq API key
4. Open chatbot.ipynb in Jupyter Notebook
5. Run cells one by one

## Author

Yasha — ML Chatbot Project, 2026
