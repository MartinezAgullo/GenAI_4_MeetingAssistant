# Meeting Assistant

Generative AI-powered business meeting assistant.
AI app to transcribe and summarise discussions.

- [Open AI whishper](https://openai.com/index/whisper/): For speach to text conversion

- [Llama2 LLM:](https://llama.meta.com/llama2/) Summarise and extract key points

- [Gradio](https://www.gradio.app/): For user's friendly interface


# Installation
Installing required libraries:
> pip install transformers==4.35.2 torch==2.1.1 gradio==4.17.0 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.19.4


To install OpenAI Whisper:
> brew install ffmpeg
> pip install git+https://github.com/openai/whisper.git


# Run the simple version
execute:
> python3.9 speech_to_text_simple.py
output:
'''
Hello, I want to speak fast because I want to test four speech-to-text applications. Today, whether it's sunny, with a slight breeze, making it perfect for outdoor activity, later I plan for a busy local part, maybe even a picnic. The test is designed to assess the accuracy and responsiveness of the speech-to-text feature. Thank you for participating in this test.
'''

# Run the web app
>  python3.9 speech_to_text.app.py