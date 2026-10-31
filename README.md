# Chat With Me — AI Portfolio Assistant

An AI-powered personal portfolio chatbot built with Python, Streamlit, and Groq.

## Overview

Chat With Me allows visitors to ask questions about Valarmathi O's professional background, skills, education, and projects through a conversational interface.

## Features

- Interactive AI chat interface
- Portfolio information loaded from JSON
- Knowledge base integration
- Project and skills explanations
- Responses that acknowledge missing information instead of inventing personal details
- Groq API integration
- Streamlit web interface

## Technology Stack

- Python
- Streamlit
- Groq API
- JSON
- python-dotenv

## Project Structure

```text
chat-with-me-portfolio/
├── app.py
├── requirements.txt
├── .env
├── README.md
└── data/
    ├── profile.json
    └── knowledge_base.txt
```

## Setup

1. Install Python.
2. Open a terminal in the project directory.
3. Create and activate a virtual environment if needed.
4. Install dependencies:

   ```powershell
   python -m pip install -r requirements.txt
   ```

5. Add your Groq API key to `.env`:

   ```text
   GROQ_API_KEY=your_groq_api_key_here
   ```

6. Start the application:

   ```powershell
   python -m streamlit run app.py
   ```

7. Open the local URL displayed in the terminal.

## Testing

The following functional checks were reported as passing:

- Professional background question
- Project and technology explanation
- Missing education details handled without inventing an answer

Python syntax and required-file checks also passed.

## Security

- Never commit `.env` or expose API keys.
- Do not publish API credentials in screenshots or reports.
- Keep personal portfolio information accurate and up to date.

## Project Status

Core chatbot functionality tested successfully. Review the interface and deployment configuration before public release.
