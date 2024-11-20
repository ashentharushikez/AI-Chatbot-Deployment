AI Chatbot Deployment with Flask and JavaScript

Description
This project demonstrates the deployment of an AI-powered chatbot using Flask for the backend and HTML/CSS/JavaScript for the frontend. The chatbot processes user inputs, performs intent recognition using PyTorch, and generates appropriate responses. The UI is clean, responsive, and user-friendly, making it suitable for integration into larger applications.

Features

Real-Time Communication: Chatbot responds dynamically to user inputs.
Flask Backend: Lightweight and easy-to-extend backend for processing requests.
Machine Learning Integration: Natural Language Processing (NLP) using a PyTorch-based model.
Frontend-Backend Decoupling: The frontend can be deployed as a standalone app or tightly integrated with the Flask backend.
Customizable: Modify intents.json to create your own chatbot with tailored responses.

Deployment Options

Flask App with Jinja2 Templates:
The frontend (HTML/CSS/JavaScript) is served by Flask using Jinja2 templates.
Standalone Frontend:
The Flask API serves predictions, and the frontend can run independently with minimal modifications.
