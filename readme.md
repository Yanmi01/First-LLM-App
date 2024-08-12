# A Basic LLm Q&A system using FastAPI

This repository contains the code for my first LLM project. Remember to first install the requirements before running the app.

To run app.py, run the code below in your terminal
'''uvicorn app:app --host 127.0.0.1 --port 5000 --reload

Feel free to update the host and port number to any other choice values
For testing in Postman, try:
'''    {
        "question": "Which is bigger? 9.11 or 9.9?",
        "model": "llama-3.1-8b-instant",
        "temperature": 0.2
    }
