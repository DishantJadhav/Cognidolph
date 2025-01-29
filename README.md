# Cognidolph
# AI Response API

This project is a Django-based API that simulates the generation of AI responses based on user input. It includes the use of **REST Framework** for creating and managing API endpoints. The project simulates response generation based on prompts and stores the results in a database.

## Features

- **Create Response**: Simulate an AI-generated response based on the given prompt.
- **Caching**: Response data is cached for 15 minutes to optimize performance.
- **Simulated AI Response**: The response is generated dynamically and contains a simulated processing time.
- **JSON Input**: Accepts user input in JSON format with fields like `prompt` and `model_used`.
- **Status Updates**: Tracks the processing status of the response (e.g., completed).

## Technologies Used

- **Django**: Backend framework for handling API requests and responses.
- **Django REST Framework**: Used to build the API endpoints.
- **SQLite**: Default database used for storing AI responses.
- **Cache**: Implemented using Django’s caching framework for optimizing repeated queries.


