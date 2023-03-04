### Description

This code is a demonstration of a chatbot that uses the OpenAI ChatGPT API to provide responses to text inputs.
It is launched using the Gradio library, which allows the user to enter text queries from a nice interface and receive responses from the chatbot.

## Install Dependencies

Run:
```bash
pip install -r requirements.txt
```

## OPENAI API Key

The app will need an OpenAI API Key to work.
To specify it, create a .env file and write your OpenAI API key
```bash
OPENAI_API_KEY=XXXXXXXXX
```

## Start The App

Just run:
```bash
gradio mywebgpt.py
```