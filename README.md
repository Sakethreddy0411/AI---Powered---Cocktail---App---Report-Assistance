# AI-Powered Cocktail Recommendation and Chatbot System

## Project Overview

The AI-Powered Cocktail Recommendation and Chatbot System is a smart web-based application developed to help users discover cocktail recipes and interact with an AI chatbot. The system uses Gemini AI to provide intelligent responses, cocktail suggestions, ingredient details, and preparation methods.

The application is built using FastAPI and integrates authentication, chat history management, and database support to provide a secure and interactive user experience.

---

# Features

* AI-powered cocktail recommendation system
* Interactive chatbot using Gemini AI
* User registration and login system
* JWT-based authentication and authorization
* Chat history storage
* Secure backend APIs
* Database integration
* Fast and scalable backend architecture
* User-friendly interface

---

# Technologies Used

## Frontend

* HTML
* CSS
* JavaScript

## Backend

* Python
* FastAPI
* Uvicorn

## Database

* SQLite / SQLAlchemy

## AI Integration

* Google Gemini AI API

## Authentication

* JWT Authentication
* Passlib for password hashing

---

# Frameworks and Libraries

## Frameworks

* FastAPI
* SQLAlchemy
* Pydantic
* Uvicorn

## Libraries

* python-jose
* passlib
* requests / httpx
* google-generativeai
* datetime
* json
* os

---

# System Modules

## User Authentication Module

Handles user registration, login, and JWT token generation.

## Chatbot Module

Communicates with Gemini AI and generates intelligent responses.

## Cocktail Recommendation Module

Provides cocktail suggestions and recipe information.

## Database Module

Stores user details, authentication data, and chat history.

## API Module

Manages communication between frontend and backend.

---

# Working Process

1. User registers or logs into the system.
2. User enters a message or cocktail query.
3. Frontend sends the request to backend APIs.
4. Backend processes the request.
5. Gemini AI generates a response.
6. Response is returned to the frontend.
7. Chat history is stored in the database.

---

# API Used

## Gemini AI API

Used for:

* AI chatbot communication
* Cocktail recommendations
* Intelligent text generation

---

# Advantages

* Smart and interactive chatbot
* Personalized cocktail suggestions
* Fast API performance
* Secure authentication system
* Easy-to-use interface
* Scalable backend architecture

---

# Future Enhancements

* Voice-enabled chatbot
* Mobile application support
* Personalized user recommendations
* Multi-language support
* Advanced cocktail filtering
* Image-based drink recognition

---

# Conclusion

The AI-Powered Cocktail Recommendation and Chatbot System successfully combines artificial intelligence with modern web development technologies. The project provides users with an intelligent and interactive platform for discovering cocktail recipes and communicating with an AI chatbot. It demonstrates the practical implementation of FastAPI, AI integration, authentication systems, and database management in a real-world application.

---

# Installation Steps

## Clone the Repository

```bash
git clone <repository-link>
```

## Navigate to Project Folder

```bash
cd project-folder
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
uvicorn main:app --reload
```

---

# Author

Developed as an academic/project work for learning AI integration, FastAPI development, and chatbot systems.
