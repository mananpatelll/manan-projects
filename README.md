# AI-Based Admission Inquiry Chatbot

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

##Introduction

The AI-Based Admission Inquiry Chatbot is a project designed to assist students and prospective applicants with inquiries related to admissions. This chatbot leverages natural language processing and machine learning techniques to provide quick and accurate responses to common admission-related questions. Whether it's information about admission requirements, deadlines, or available programs, this chatbot can help.

##Features

- Instantly answers admission-related queries.
- Provides information about admission requirements, deadlines, programs, and more.
- Learns and improves its responses over time through machine learning.
- Stores chat logs in a database for future analysis.

##Getting Started

###Prerequisites

Before you can run the chatbot, ensure you have the following prerequisites:

- Python 3.x
- Flask
- Keras
- MySQL (for the database)

###Installation

1. Clone the project repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/ai-admission-inquiry-chatbot.git
   ```

2. Install the required Python packages using pip:

   ```shell
   pip install -r requirements.txt
   ```

3. Set up the MySQL database. You can do this by running the provided SQL script to create the necessary tables.

4. Run the Flask application:

   ```shell
   python app.py
   ```

Now, the chatbot should be up and running on your local machine.

##Usage

1. Access the chatbot by opening a web browser and navigating to `http://localhost:5000`.

2. Start a conversation with the chatbot. It will guide you through the admission inquiry process, asking for your name and mobile number before you can start chatting.

3. Ask questions related to admission, and the chatbot will provide responses based on its training data and machine learning model.

##Project Structure

The project's directory structure is organized as follows:

- `app.py`: Contains the main Flask application and chatbot logic.
- `train.py`: Used to train the machine learning model based on provided intent patterns.
- `templates/chat.html`: HTML template for the chat interface.
- `static`: Directory for static assets like images and CSS.
- `intents.json`: Configuration file containing intent patterns and responses.
- `words.pkl` and `classes.pkl`: Pickled files storing processed words and classes.
- `chatbot_model.h5`: Trained machine learning model.

