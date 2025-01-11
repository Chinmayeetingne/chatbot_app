# Chatbot Application

Overview

This Chatbot Application is an interactive conversational assistant built using Python, Streamlit, and scikit-learn. It is designed to recognize user intents and provide relevant responses, making it useful for handling FAQs, sharing tips, or simply engaging in casual conversations.

Features

Interactive Chat Interface: Users can interact with the chatbot via a simple, user-friendly Streamlit web app.

Intent Recognition: Utilizes Natural Language Processing (NLP) techniques to identify user intents from predefined patterns.

Custom Responses: Provides meaningful and engaging responses for each recognized intent.

Expandable Dataset: Easy to add new intents, patterns, and responses.

Technologies Used

Python: Core programming language.

Streamlit: Framework for creating a web-based chatbot interface.

scikit-learn: Used for vectorizing text data and intent classification.

NLP: Implemented for text preprocessing and classification.


chatbot-app/
|
|-- ChatBot_app.py         # Main application script
|-- intents.json           # Intent dataset with patterns and responses
|-- requirements.txt       # Dependencies for the project
|-- README.md              # Project documentation (this file)

How It Works

Intent Recognition:

User input is vectorized using scikit-learn's TfidfVectorizer.

A trained classifier predicts the intent based on the input text.

Response Generation:

The chatbot matches the predicted intent with predefined responses.

A random response from the matched intent is selected and displayed.

Streamlit Integration:

The Streamlit interface allows real-time conversations with the chatbot.

Example Intents

{
    "tag": "greeting",
    "patterns": ["Hi", "Hello", "Hey"],
    "responses": ["Hello! How can I assist you?", "Hi there!", "Hey! Need help?"]
}

How to Customize

Open the intents.json file to add or modify intents.

Define:

tag: A unique identifier for the intent.

patterns: List of user inputs associated with the intent.

responses: List of responses the chatbot can provide.

Save the file and rerun the app.

Future Enhancements

Integration with APIs (e.g., weather, news, or other real-time services).

Addition of a database to log conversations.

Deployment to cloud platforms for public access.

Advanced NLP techniques for better intent recognition.

License

This project is open-source and available under the MIT License.

Contact

For questions or suggestions, please contact:

Name: Chinmayee Tingne

Email: rashitingne12@gmail.com

Feel free to explore, use, and enhance this chatbot application!

