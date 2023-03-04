### Description
This code is a demonstration of a chatbot that uses the OpenAI ChatGPT API to provide responses to text inputs.
It is launched using the Gradio library, which allows the user to enter text queries from a nice interface and receive responses from the chatbot.

### Usage
First install the packages in the requirements.txt file with the following command
'''
pip install -r requirements.txt
'''

Then create a .env file and write in your OpenAI API key.
'''
OPENAI_API_KEY=XXXXXXXXX
'''

Finally run your app.
'''
gradio mywebgpt.py
'''