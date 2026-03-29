
# AI Quiz Generator

A Streamlit app that automatically generates multiple choice questions from a PDF using a local AI model via Ollama.

## Features
- Upload any PDF → automatic question generation
- Interactive quiz with answer validation and explanations
- Adjustable number of questions (3 to 30) but you can change it up by yourself
- 100% local, no API key required ($$$)

## Installation
pip install -r requirements.txt
ollama pull llama3

## Run the app
streamlit run quizApp.py

## Tech stack
- Python
- Streamlit
- Ollama (llama3)
- pdfplumber
