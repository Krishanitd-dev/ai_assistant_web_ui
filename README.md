# Full-Stack AI Web Application
The project demonstrates modern full-stack development practices by combining a FastAPI backend, interactive frontend interface, database integration, and AI API services.

Users can submit questions, receive generated responses, view conversation history, and interact with the application through a clean and responsive user interface.

Frontend:
HTML
CSS
Jinja2 templates
JavaScript

Backend:
FastAPI (Python)
Uvicorn

AI:
Groq API 
Llama model

Database:
SQLite

Deployment
Vercel
GitHub

## Features
AI-powered question answering
Interactive AI chat interface
FastAPI backend architecture
Groq API integration for LLM responses
Conversation history storage
SQLite database integration
Character counter for user input
Copy AI response functionality
Dark mode support
Responsive design for different screen sizes

### installation

python -m venv venv
.\venv\Scripts\activate


python -m pip install fastapi uvicorn jinja2 python-dotenv openai python-multipart reportlab


##### pdf
pip install reportlab

pip freeze > requirements.txt


pip install -r requirements.txt


## Run 
.\venv\Scripts\activate
python -m uvicorn app.main:app --reload

## Vercel Deployment Notes
SQLite is used for local development. On Vercel, conversation history and delete features may not persist due to the serverless environment. For production, use a cloud database.
## Update
Updated requirements.txt and saved it as UTF-8 encoding.