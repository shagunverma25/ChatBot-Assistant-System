# Chatbot-Assistant-System
(Using Python, ML Algorithm, NLP Toolkit, Flask and Javascript)

The Chatbot is a Python based chatbot that utilizes ML algorithm and NLP techniques to provide automated assistance to users with related inquiries. The chatbot aims to improve the user experience by delivering quick and accurate responses to their questions.
This project demonstrates the deployment of a chatbot using Flask for the backend and JavaScript for the frontend. The chatbot is trained using a feedforward neural network implemented in PyTorch and uses pre-defined intents to respond to user queries.

## Features

- Backend: Flask-based prediction API
- Frontend: Interactive chat interface built with HTML, CSS and JavaScript
- Neural Network: Feedforward neural network trained with PyTorch
- Extensible: Easy to modify intents and responses in `intents.json`
- Deployment: Serve the Flask API separately and connect it to the frontend.


## Project Structure

- `intents.json`: File containing training data for the chatbot.
- `train.py`: Script to train the chatbot using a feedforward neural network.
- `chat.py`: Console-based testing of the chatbot.
- `app.py`: Flask application for serving the chatbot's backend.
- `frontend`: Contains the frontend JavaScript, CSS, and HTML files.


## Dependencies

pip install Flask torch torchvision nltk
