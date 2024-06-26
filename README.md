# ChatBot-using-Python-and-OpenAI

This project is a simple chatbot implemented using OpenAI's GPT-3.5-Turbo model in Python. The chatbot interacts with users by taking their input and generating AI-driven responses until the user decides to end the conversation.

## Introduction       

The goal of this project is to create a basic chatbot that can converse with users in natural language. It utilizes OpenAI's powerful GPT-3.5-Turbo model to generate responses based on the user's input. The chatbot runs in a loop, continually accepting user questions and providing relevant responses until the user types "bye" to terminate the session.

## Installation        

To get started with this project, you need to clone the repository and install the necessary dependencies. The primary dependencies for this project are the openai package for interacting with the OpenAI API and the python-dotenv package for managing environment variables.

## Setup       

Before running the chatbot, you need to set up your environment:        


Obtain an API key from OpenAI by signing up on their website.         

Create a .env file in the root directory of the project and add your OpenAI API key to it. This allows the application to authenticate and interact with the OpenAI API securely.
Usage         

To use the chatbot, simply run the Python script. The chatbot will prompt you to enter a question. You can continue asking questions, and the chatbot will generate responses using the GPT-3.5-Turbo model. If you type "bye", the chatbot will exit the loop and terminate the session.
